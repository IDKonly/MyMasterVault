---
creation_date: <% tp.file.creation_date(string = "YY.MM.DD") %>
note_type: daily_note
aliases:
  - <% tp.date.now("YY년 MM월 DD일", 0, tp.file.title, "YY.MM.DD") %>
tags:
  - daily_note
PARA:
  - Archive
---

<< [[<% tp.date.now("YY.MM.DD", -1, tp.file.title, "YY.MM.DD") %>]] | [[<% tp.date.now("YY.MM.DD", 1, tp.file.title, "YY.MM.DD") %>]] >>

---
<%*
let yesterday = tp.date.now("YY년 MM월/YY.MM.DD", -1, tp.file.title, "YY.MM.DD");
let section = "## To Do";
let default_value = "\n## To Do\n-  \n-  \n-  \n";
let should_include = 0;
let yfile = tp.file.find_tfile(yesterday);
if(yfile) {
	const content = await app.vault.read(yfile);
	if(content.contains(section)) {
		should_include = 1;
	} 
} 
if(!should_include) {
	tR += default_value;
}
%>
<%* if(should_include) { %><% tp.file.include("[["+yesterday+section+"]]") %><%* } %>
# Memo
1.  

## daily_cal