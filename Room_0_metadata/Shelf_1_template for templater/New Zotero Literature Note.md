---
type: Zotero Literature Note
publish-year: {{date | format("YYYY")}} 
created: {{importDate | format("YY.MM.DD")}}
PARA:
  - Archive
tags: {% for t in tags %} 
- {{t.tag | replace(" ", "-")}}{% endfor %}
- zotero
- note/zotero
---
## Notes
{% persist "notes" %}{% if isFirstImport %}
- Critique
	- Pros
	- Cons
- How is it relevant to my research?
	- Relevant_Topic::
	- Use::
{% endif %}
{% endpersist %}
External note : [[Room_3_Lab/Shelf_2_library/Box_3_Memo for manuscripts/@{{citekey}}]]

> [!Cite]  
> {{bibliography}}

>[!Info]  {%- for attachment in attachments | filterby("path", "endswith", ".pdf") %} [{{attachment.title}}](file://{{attachment.path | replace(" ", "%20")}}) {%- endfor -%}. [to Zotero]({{desktopURI}})
> {%- for creator in creators %} {%- if creator.name == null %} **{{creator.creatorType | capitalize}}**::{{creator.lastName}}, {{creator.firstName}}{%- endif -%}<br>  
> {%- if creator.name %}**{{creator.creatorType | capitalize}}**:: {{creator.name}}{%- endif -%}{%- endfor %}  
> **Title**:: {{title}}  
> **Year**:: {{date | format("YYYY")}}  
> **Citekey**:: @{{citekey}}  
> {%- if itemType %}**itemType**:: {{itemType}}{%- endif %}  
> {%- if itemType == "journalArticle" %}**Journal**:: *{{publicationTitle}}* {%- endif %}  
> {%- if volume %}**Volume**:: {{volume}} {%- endif %}  
> {%- if issue %}**Issue**:: {{issue}} {%- endif %}  
> {%- if itemType == "bookSection" %}**Book**:: {{publicationTitle}} {%- endif %}  
> {%- if publisher %}**Publisher**:: {{publisher}} {%- endif %}  
> {%- if place %}**Location**:: {{place}} {%- endif %}  
> {%- if pages %} **Pages**:: {{pages}} {%- endif %}  
> {%- if DOI %}**DOI**:: {{DOI}} {%- endif %}  
> {%- if ISBN %}**ISBN**:: {{ISBN}} {%- endif %}

> [!LINK]  


> [!Abstract]  
> {%- if abstractNote %}  
> {{abstractNote}}  
> {%- endif -%}

{%- set important = annotations | filterby("comment", "startswith", "important") -%}  
{%- if important.length > 0 %}

> [!important] Callouts  
{%- for annotation in important -%}  
{%- if annotation.annotatedText %}  
> - {{annotation.annotatedText | nl2br}}  
{%- endif -%}  
{%- if annotation.imageRelativePath %}  
> - ![[{{annotation.imageRelativePath}}]]  
{%- endif %}  
> [page {{annotation.page}}](file://{{annotation.attachment.path | replace(" ", "%20")}})  
{%- endfor -%}  
{%- endif %}  
{%- if annotations.length %}



## Annotations  
{%- endif %}

{%- macro calloutHeader(type, color) -%}  
{%- if type == "highlight" -%}  
<mark style="background-color: {{color}}">Highlight</mark>  
{%- endif -%}

{%- if type == "text" -%}  
Note  
{%- endif -%}  
{%- endmacro -%}

{%- set annots = annotations | filterby("date", "dateafter", lastExportDate) -%}  
{%- if annots.length > 0 %}  
### Exported: {{exportDate | format("YYYY-MM-DD a h:mm ")}}

{% for annot in annots -%}  
> {{calloutHeader(annot.type, annot.color)}}  
{%- if annot.annotatedText %}  
> {{annot.annotatedText | nl2br}}  
{%- endif -%}  
{%- if annot.imageRelativePath %}  
> ![[{{annot.imageRelativePath}}]]  
{%- endif %}  
> [page {{annot.page}}]({{annot.desktopURI}}) [[{{annot.date | format("YY.MM.DD")}}|{{annot.date | format("YYYY-MM-DD#a h:mm")}}]]  
{%- if annot.comment %}  
> - {{annot.comment | nl2br}}  
{% endif %}

{% endfor -%}  
{% endif -%}