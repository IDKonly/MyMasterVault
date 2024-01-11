---
creation_date: 23.10.05
last_modified: 
note_type: basic
category: 
memo_level: 
aliases: 
tags: 
Status:
  - Working
PARA:
  - Project
---

# 국문본문
## 초안
1. RNA transcription가 전사인자의 모집부터 전사종결(transcription terminaiton)까지 잘 조절되는 것은 정상적인 단백질 발현에 중요하다.
	1. DNA를 감고 있는 Histone의 posttranslational modificaiton은 진핵세포의 유전자 전사에 영향을 미치고, histone의 특정 라이신 잔기의 methylation은 유전자 전사의 활성과 관련이 있다.
	2. 특히 H3의 4번째 라이신 잔기(H3K4)는 RNA polymerase2에 의해서 활발히 전사되는 유전자에 풍부하게 나타나는 대표적인 histone posttranslational modification이다.
	3. H3K4의 메틸화는 전사가 풍부하게 일어나면 일어날수록 더 많이 나타난다. [Lm *et al.*, 2017](zotero://select/items/@lm2017)
	4. 엄 나 글 개못쓰네
2. [[Saccharomyces cerevisiae]]에서 histone의 posttranslational modification은 RNA의 정상적인 발현에 중요하다고 알려져 있다. 특히 H3의 4번째 라이신 잔기(H3K4)의 아세틸화와 메틸화는 RNA의 발현에 많은 영향을 미친다.
3. [[Saccharomyces cerevisiae|S. cerevisiae]]에서 H3K4 메틸레이션을 일으키는 유일한 complex로 알려진 COMPASS는 complex의 platform으로 작용하는 Set1을 제외한 7개의 subunit([Bae *et al.*, 2020](zotero://select/items/@bae2020)의 intro 참고, Bre2, Sdc1, Shg1, Spp1, Swd1, Swd2, Swd3)으로 이루어져 있다.
	1. 주목해야 할 것은 COMPASS의 구성요소중 Swd2만이 S. cerevisiae에서 essential하다는 것이다. (뒤로 빼거나 단독단락으로 써야할듯)
	2. 심지어 set1이 결실되었을 때, COMPASS가 만들어지지 못함에도 불구하고, 세포가 살아남을 수 있다는 것을 고려해보면 Swd2가 세포 내에서 COMPASS의 구성요소로서의 기능 이외의 중요한 기능을 하고 있음을 알 수 있다.
4. [[Cleavage and Polyadenylation Factor|CPF]] complex는 전사 종결단계에서 RNA pol2와 직접적으로 결합하며, poly adenylation과 전사의 종결 모두에 필요한 중요한 complex이다.
	1. CPF complex의 subcomplex인 APT subcomplex 또한 Swd2를 포함하고 있다.
		1. APT의 기능은 구체적으로 밝혀지지 않았지만([Mischo *et al.*, 2013](zotero://select/items/@mischo2013)) 3’ end processing의 finetuning에 관여할 것으로 예측되고 있다.
		2. 와 나 APT에 대해서 아는게 없네… 
5. Homo sapiens의 Swd2 homologue인 WDR82는 human Set1-COMPASS complex이며, 동시에 Swd2와 비슷하게 전사종결에도 관여한다.
6. Swd2 결실균주는 성장에 결함이 있다.
	1. COMPASS가 없는 dset1 균주에서는 Swd2의 결실이 성장에 결함을 일으키지 않기 때문에(?) Swd2의 결실로 인한 성장결함은 COMPASS 때문이 아닌 Swd2를 포함하고 있는 다른 complex인 APT complex의 결함으로 인한 것이라고 알려졌었으나. [Nedea *et al.*, 2008](zotero://select/items/@nedea2008)
	2. [Soares *et al.*, 2012](zotero://select/items/@soares2012)에서 Swd2로 인한 성장결함이 CPF의 기능적 문제 뿐만이 아닌 COMPASS 또한 연루된 문제 때문에 일어난다는 연구결과가 보고되면서 Swd2의 두가지 기능이 서로 독립적이지 않고 연관되어 있을 가능성이 제시되었다.
7.  때문에, Swd2의 기능적 연구는 쉽지 않다.

## 초고
진핵세포의 DNA는 8개의 단백질이 결합되어 있는 histone octamer에 감긴 nucleosome의 형태를 기본 구조로 패키징 되어 있다. Nucleosome은 느슨한 혹은 밀집된 구조를 만들고 이들을 각각 euchromatin(진정염색질), heterochromatin(이질염색질)이라 부르고, 이들이 세포 내 염색체의 대부분을 구성하고 있다

많은 유전자들이 nucleosome이 고밀도로 모여 있는 heterochromatin에 위치하고 있다. Heterochromatin에 있는 유전자는 그 구조적 특징 때문에 RNA polymerase의 접근이 어렵고, 그 결과 RNA polymerase의 접근이 제한된 유전자는 RNA transcription가 정상적으로 개시되지 않는다.

때문에 원활한 유전자의 transcription을 위해서는 heterochromatin을 느슨하게 하여 RNA polymerase의 accessibility를 증가시키는 것이 필요하고, 이 과정에서 histone의 주요 잔기에 acetylation, methylation, ubiquitination, phosphorylation 등의 epigenetic mechanism이 유효하게 작용한다. 이렇게 histone의 주요한 잔기를 변형시키는 것을 histone modification(히스톤 변형, histone posttranslational modification 또는 histone PTM)이라고 한다.

Histone modification은 histone의 전하에 변화를 주어 DNA 혹은 인접한 histone과의 interaction의 변화를 유발해 chromatin의 구조를 변형시키거나, 다른 transcription 조절자들을 추가적으로 모집하는 등의 역할을 통해 RNA transcription에 영향을 줄 수 있다. 이러한 histone modification 중 acetylation과 methylation에 관한 연구가 활발하고 그에 따라 이들의 작용이 잘 알려져 있다.

Histone의 acetylation은 주로 transcription 활성에 기여하는 것으로 그 영향이 비교적 명료하게 알려져 있으나, methylation의 경우 여러 잔기가 modification의 target이 되며 mono-, di-, trimethylation으로 그 변화의 종류가 많고 그로 인해서 생기는 효과 또한 다양하기 때문에 많은 연구자들이 연구를 하고 있는 분야이다.

Histone methylation의 대상이 되는 잔기 중 H3의 네번째 lysine 잔기(H3K4)에서 일어나는 trimethylation(H3K4me3)은 비교적 그 패턴이 명확히 알려진 histone modification중 하나이다. H3K4me3는 각 유전자의 프로모터 부분에 밀집하여 존재하며, 소수의 예외를 제외하고 각 유전자의 H3K4me3의 수준은 해당 유전자의 transcription 활성도와 양의 상관관계가 있다는 것이 알려져 있다.

_Saccharomyces cerevisiae_ 의 H3K4 methylation은 유일하게 COMPASS(**COMP**lex **AS**sociated with **S**et1 또는 Set1C)에 의해서 매개된다. COMPASS는 H3K4 methyltransferase인 Set1 단백질을 플랫폼으로 Set1의 활성을 조절하는 7개의 subunit(Spp1, Shg1, Sdc1, Bre2, Swd1, Swd2, Swd3)가 결합한 구조의 단백질이다.

특이하게, COMPASS의 구성요소 중 오직 Swd2만이 S. cerevisiae의 생존에 필수적인 단백질이다. 심지어 플랫폼 역할을 하는 Set1이 결실되어 COMPASS가 세포내에서 사라졌음에도 불구하고 세포가 생존하는 데에는 영향이 없었으나 subunit인 Swd2가 결실되었을 때에는 세포가 생존할 수 없다, 그러므로 Swd2는 COMPASS내에서의 기능 이외에 주요한 역할을 할 것이고 이것이 Swd2의 lethality의 원인이라고 예상되었다.

RNA transcription termination과 3’ end processing에 관여하는 complex인 CPF(**C**leavage and **P**olyadenylation **F**actor)는 Swd2를 포함한 APT(**A**ssociated with **Pt**a1) subcomplex를 구성요소로 가지고 있는 거대한 단백질 복합체이다. CPF는 phosphatase module인 APT 이외에도 polymerase module과 nuclease module을 포함한 Core CPF로 이루어져 있다. (Lidschreiber et al. 2018) 즉, CPF는 polymerase, nuclease, phosphatase module을 모두 포함하고 있다. 그러나 각 모듈이 어떤 방식으로 결합되어 있는지는 아직까지 불분명하다.

CPF에 포함되어 있는 APT subcomplex의 구성요소의 변이는 yeast의 non-polyadenylated snoRNA의 termination defect를 일으킨다. APT의 구성요소 중 Swd2와 함께 Glc7, Pti1 그리고 Ssu72이 essential protein이고, 이 중 결실되었을 때 snoRNA의 termination defect가 일어나는 것으로 잘 알려진 단백질은 Swd2와 Glc7이다. Swd2는 APT subcomplex에서 Glc7이 분리되지 않도록 하는 역할을 해서 궁극적으로는 APT subcomplex의 안정성에 기여를 한다. 그렇기 때문에, Swd2의 결실로 인한 성장결함은 COMPASS의 기능과는 무관하게 APT subcomplex의 결함으로 인한 CPF 활성 저해 때문인 것으로 생각되어 왔다.

그러나 2012년 Soares와 Buratowski의 연구결과에 따르면 Swd2의 lethality는 Swd2를 포함하고 있는 complex 중 하나의 기능이상에 의한 문제가 아니라, COMPASS와 CPF complex간 상호작용이 Swd2의 결실로 인해 정상적으로 이루어지지 않게 되면서 나타나는 현상이다 (Soares and Buratowski, 2012). 또한 잠재적으로 Swd2가 COMPASS와 CPF 각각에서 독립적으로 기능하고 있지 않고 서로 연관되어 있을 수 있다는 것이 제안된 바 있다 (Park and Lee, 2017).

Yeast부터 human까지 Swd2는 기능적, 서열적으로 모두 잘 보존되어 있다. Drosophila melanogaster와 Homo sapiens에서 발현되는 Wdr82는 잘 알려진 Swd2 homology protein이고, Human의 WDR82는 Swd2와 비교해 아미노산 서열에서 93%, DNA 서열에서 95%가 동일하다 (Wu et al., 2008). 또한 잘 보존되어 있는 인간의 COMPASS-like complex중 Setd1a와 Setd1b(이 표기가 맞나?)를 플랫폼으로 한 Set1-COMPASS의 subunit이다. Swd2는 COMPASS-like complex에서 H2Bub 의존성을 유발하는 특징 또한 잘 보존하고 있다. (Shilatifard, 2012) 또한 WDR82는 PNUTS의 major binding partner이다. PNUTS는 또한 Glc7의 human homologue인 PP1과도 함께 결합하는데, 이는 APT complex가 WDR82를 포함한 PP1 complex 형태로 진화적으로 보존되어 있다는 것을 의미한다 (Lee et al. 2010). 게다가 후속 연구에서는 이들이 APT complex와 비슷하게 transcription termination과 밀접한 연관성이 있다는 것이 밝혀졌다 (Austenaa et al. 2015).

Swd2가 진화적으로 잘 보존되어 있다는 사실은 잠재적으로 Swd2가 RNA transcription 조절에서 중추적인 역할을 맡고 있을 가능성이 크다. 즉, Swd2의 연구가치는 크다고 할 수 있다. 하지만 상술한 Swd2가 yeast에서 가지는 lethality 때문에 해당 연구는 아직 충분하지 않은 실정이다. 물론 우회적인 방법을 통한 조건부 Swd2 결실 균주를 만들거나, Ref2 또는 helicase 활성이 없는 Sen1 절편을 과발현 하는 방법으로 Swd2의 결실로 인한 사멸을 억제하여 Swd2 결실 균주를 만들 수 있다. 하지만 이런 방법은 야생형 균주에서 단순히 Swd2만 결실된 조건과 엄연히 다른 상황이기 때문에, 온전히 Swd2의 기능을 연구하기에는 어렵다.

 본 논문에서 우리는 현재까지 Swd2에 대해서 알려진 정보를 취합하고, 앞으로 해야 하는 연구를 제시할 것이다.


# References
## Basic description of Transcription (initiation and termination)


베이직한 설명의 맥락은 [Dichtl *et al.*, 2004](zotero://select/items/@dichtl2004)의 indtroduction을 참고하자.
### initiation
1. 
### termination 
1. Mischo, H. E. & Proudfoot, N. J. Disengaging polymerase: Terminating RNA polymerase II transcription in budding yeast. Biochimica et Biophysica Acta (BBA) - Gene Regulatory Mechanisms 1829, 174–185 (2013).
2. Terzi, N., Churchman, L. S., Vasiljeva, L., Weissman, J. & Buratowski, S. H3K4 trimethylation by Set1 promotes efficient termination by the Nrd1-Nab3-Sen1 pathway. Mol Cell Biol 31, 3569–3583 (2011).

1. [Dichtl *et al.*, 2004](zotero://select/items/@dichtl2004)
	1. Swd2p is required for 3’ end formation of specific mRNAs and snoRNAs
2. [Mischo *et al.*, 2013](zotero://select/items/@mischo2013)
	1. *For others, such as snoRNA, snRNA and CUTs, transcript processing and termination depend on components of the CPF, CFI and the NRD complex (aka Nrd1-Nab3-Sen1-dependent pathway).*
3. [Terzi *et al.*, 2011](zotero://select/items/@terzi2011)
	1. Set1과 Nrd1 dependent termination의 연관성 
4. [Soares *et al.*, 2012](zotero://select/items/@soares2012)
	1. antagonic한 관계성을 통한 initiation과 termination의 연속
## Histone posttranslational modification (PTM) regulation in transcription
### COMPASS and CPF, the complex of transcription regulator include Swd2
1. Niño, C. A., Hérissant, L., Babour, A. & Dargemont, C. mRNA Nuclear Export in Yeast. Chem. Rev. 113, 8523–8545 (2013).
2. Vitaliano-Prunier, A. et al. H2B ubiquitylation controls the formation of export-competent mRNP. Mol Cell 45, 132–139 (2012).
## Swd2 Orthologues 

## Limitation in study of Swd2 because cell has lethality in absence Swd2
1. [Soares *et al.*, 2012](zotero://select/items/@soares2012)를 강하게 참고