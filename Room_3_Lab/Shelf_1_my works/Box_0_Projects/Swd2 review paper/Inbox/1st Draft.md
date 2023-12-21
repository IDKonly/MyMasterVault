---
creation_date: 23.11.03
last_modified: 
note_type: basic
category: 
memo_level: 
aliases: 
tags: 
PARA:
  - Archive
---


# Introduction

진핵세포의 DNA는 8개의 단백질이 결합되어 있는 histone octamer에 감긴 nucleosome의 형태를 기본 구조로 패키징 되어 있다. Nucleosome은 느슨한 혹은 밀집된 구조를 만들고 이들을 각각 euchromatin(진정염색질), [[heterochromatin]](이질염색질)이라 부르고, 이들이 세포 내 염색체의 대부분을 구성하고 있다

많은 유전자들이 nucleosome이 고밀도로 모여 있는 [[heterochromatin]]에 위치하고 있다. [[Heterochromatin]]에 있는 유전자는 그 구조적 특징 때문에 RNA polymerase의 접근이 어렵고, 그 결과 RNA polymerase의 접근이 제한된 유전자는 RNA transcription가 정상적으로 개시되지 않는다.

때문에 원활한 유전자의 transcription을 위해서는 [[heterochromatin]]을 느슨하게 하여 RNA polymerase의 accessibility를 증가시키는 것이 필요하고, 이 과정에서 histone의 주요 잔기에 acetylation, methylation, ubiquitination, phosphorylation 등의 epigenetic mechanism이 유효하게 작용한다. 이렇게 histone의 주요한 잔기를 변형시키는 것을 histone modification(히스톤 변형, histone posttranslational modification 또는 histone PTM)이라고 한다 (Venkatesh & Workman, 2015).

Histone modification은 histone의 전하에 변화를 주어 DNA 혹은 인접한 histone과의 interaction의 변화를 유발해 chromatin의 구조를 변형시키거나, 다른 transcription 조절자들을 추가적으로 모집하는 등의 역할을 통해 RNA transcription에 영향을 줄 수 있다. 이러한 histone modification 중 acetylation과 methylation에 관한 연구가 활발하고 그에 따라 이들의 작용이 잘 알려져 있다 (Venkatesh & Workman, 2015).

Histone의 acetylation은 주로 transcription 활성에 기여하는 것으로 그 영향이 비교적 명료하게 알려져 있으나(Kurdistani & Grunstein, 2003), methylation의 경우 여러 잔기가 modification의 target이 되며 mono-, di-, trimethylation으로 그 변화의 종류가 많고 그로 인해서 생기는 효과 또한 다양하기 때문에 많은 연구자들이 연구를 하고 있는 분야이다.

Histone methylation의 대상이 되는 잔기 중 H3의 네번째 lysine 잔기(H3K4)에서 일어나는 trimethylation(H3K4me3)은 비교적 그 패턴이 명확히 알려진 histone modification중 하나이다. H3K4me3는 각 유전자의 프로모터 부분에 밀집하여 존재하며, 소수의 예외를 제외하고 각 유전자의 H3K4me3의 수준은 해당 유전자의 transcription 활성도와 양의 상관관계가 있다는 것이 알려져 있다 (Santos-Rosa et al., 2002).

_[[Saccharomyces cerevisiae]]_ 의 H3K4 methylation은 유일하게 [[COMPASS]](**COMP**lex **AS**sociated with **S**et1 또는 [[COMPASS|Set1C]])에 의해서 매개된다. [[COMPASS]]는 H3K4 methyltransferase인 [[Set1]] 단백질을 플랫폼으로 [[Set1]]의 활성을 조절하는 7개의 subunit(Spp1, Shg1, Sdc1, [[Bre2]], Swd1, [[Swd2]], Swd3)가 결합한 구조의 단백질이다(Miller et al., 2001; Nagy et al., 2002; Roguev et al., 2001; Santos-Rosa et al., 2002).

특이하게, [[COMPASS]]의 구성요소 중 오직 [[Swd2]]만이 [[Saccharomyces cerevisiae|S. cerevisiae]]의 생존에 필수적인 단백질이다 (Cheng et al., 2004). 심지어 플랫폼 역할을 하는 [[Set1]]이 결실되어 [[COMPASS]]가 세포내에서 사라졌음에도 불구하고 세포가 생존하는 데에는 영향이 없었으나 subunit인 [[Swd2]]가 결실되었을 때에는 세포가 생존할 수 없다 (Miller et al., 2001). 그러므로 [[Swd2]]는 [[COMPASS]]내에서의 기능 이외에 중요한 역할을 할 것이고 이것이 [[Swd2]]의 lethality의 주요한 원인이라고 예상되었다.

RNA transcription termination과 3’ end processing에 관여하는 complex인 [[Cleavage and Polyadenylation Factor|CPF]](**C**leavage and **P**olyadenylation **F**actor)는 [[Swd2]]를 포함한 APT(**A**ssociated with **Pt**a1) subcomplex를 구성요소로 가지고 있는 거대한 단백질 복합체이다. [[Cleavage and Polyadenylation Factor|CPF]]는 phosphatase module인 APT 이외에도 polymerase module과 nuclease module을 포함한 Core [[Cleavage and Polyadenylation Factor|CPF]]로 이루어져 있다 (Lidschreiber et al., 2018). 즉, [[Cleavage and Polyadenylation Factor|CPF]]는 polymerase, nuclease, phosphatase module을 모두 포함하고 있다. 그러나 각 모듈이 어떤 방식으로 결합되어 있는지는 아직까지 불분명하다.

[[Cleavage and Polyadenylation Factor|CPF]]에 포함되어 있는 APT subcomplex의 구성요소의 변이는 yeast의 non-polyadenylated snoRNA의 termination defect를 일으킨다.  APT의 구성요소 중 [[Swd2]], [[Glc7]], Pta1, [[REF2|Ref2]] 그리고 Pti1이 essential protein이다. APT의 essential protein은 결실시에 snoRNA의 termination 또는 3’ end maturation에 문제가 생겨서 yeast의 생존에 영향을 미친다. 특히 [[Swd2]]는 APT subcomplex에서 [[Glc7]]이 분리(dissociation)되지 않도록 하는 역할을 해서 궁극적으로는 APT subcomplex의 구조적 무결성에 기여한다 (Nedea et al., 2008; Park & Lee, 2017). 그렇기 때문에, [[Swd2]]의 결실로 인한 성장결함은 [[COMPASS]]의 기능과는 무관하게 APT subcomplex의 결함으로 인한 [[Cleavage and Polyadenylation Factor|CPF]] 활성 저해 때문인 것으로 생각되어 왔다.

그러나 2012년 Soares와 Buratowski의 연구결과에 따르면 [[Swd2]]의 lethality는 APT complex의 기능인 snoRNA의 전사종결이 essential gene인 snR13-TRS31에서 정상적으로 일어나지 않았기 때문에 나타난다. 주목할만한 점은, [[Swd2]]의 lethality는 [[Set1]]이 결실되었을 때 완화된다 (Soares and Buratowski, 2012). 이후 추가 연구를 통해서 잠재적으로 [[Swd2]]가 [[COMPASS]]와 [[Cleavage and Polyadenylation Factor|CPF]] 각각에서 독립적으로 기능하고 있지 않고 서로 연관되어 있을 수 있다는 것이 제안된 바 있다 (Shinae Park, 2017).

Yeast부터 human까지 [[Swd2]]는 기능적, 서열적으로 모두 잘 보존되어 있다. _Drosophila melanogaster_ 와 _Homo sapiens_ 에서 발현되는 WDR82는 잘 알려진 [[Swd2]] homology protein이고, Human의 WDR82는 [[Swd2]]와 비교해 아미노산 서열에서 93%, DNA 서열에서 95%가 동일하다 (Wu et al., 2008). 또한 잘 보존되어 있는 인간의 [[COMPASS]]-like complex중 Setd1a와 Setd1b를 플랫폼으로 한 [[Set1]]-[[COMPASS]]의 subunit이다. [[Swd2]]는 [[COMPASS]]-like complex에서 H2Bub 의존성을 유발하는 특징 또한 잘 보존하고 있다 (Shilatifard, 2012). 또한 WDR82는 PNUTS의 major [[binding]] partner이다. PNUTS는 또한 [[Glc7]]의 human homologue인 PP1과도 함께 결합하는데, 이는 APT complex가 WDR82를 포함한 PP1 complex 형태로 진화적으로 보존되어 있다는 것을 의미한다 (Landsverk et al., 2020; Lee et al., 2010). 게다가 후속 연구에서는 이들이 APT complex와 비슷하게 transcription termination과 밀접한 연관성이 있다는 것이 밝혀졌다 (Austenaa et al., 2015).

[[Swd2]]가 진화적으로 잘 보존되어 있다는 사실은 잠재적으로 [[Swd2]]가 RNA transcription regulation machinery에서 중추적인 역할을 맡고 있을 가능성이 크다는 것을 의미한다. 즉, [[Swd2]]의 연구가치는 크다고 할 수 있다. 하지만 상술한 [[Swd2]]가 yeast에서 가지는 lethality 때문에 해당 연구는 아직 충분하지 않은 실정이다. 물론 우회적인 방법을 통한 조건부 [[Swd2]] 결실 균주를 만들거나, [[REF2|Ref2]] 또는 helicase 활성이 없는 Sen1 절편을 과발현 하는 방법으로 [[Swd2]]의 결실로 인한 사멸을 억제하여 [[Swd2]] 결실 균주를 만들 수 있다(Cheng et al., 2004; Nedea et al., 2008). 하지만 이런 방법은 야생형 균주에서 단순히 [[Swd2]]만 결실된 조건과 엄연히 다른 상황이기 때문에, 온전히 [[Swd2]]의 기능을 연구하기에는 어렵다.

때문에, 본 논문에서 우리는 현재까지 [[Swd2]]에 대해서 알려진 정보를 취합하고, 앞으로 해야 하는 연구를 제시할 것이다. 이는 [[Swd2]]의 중요성을 되돌아보고 지난 주요 연구 결과를 통해서 [[Swd2]]의 기능을 명확히 할 수 있을 것이다.

# Swd2

## WD repeat

WD repeat protein(혹은 WD40 protein)은 tryptophan-aspartic acid(WD)로 끝나는 WD40 domain이 반복된 서열을 가진 단백질을 말한다. WD40 domain은 44개에서 60개의 서열로 구성되며 특정 정규식(regular expression)을 따르는 핵심서열이 존재한다 (Smith et al., 1999).  WD repeat protein의 서열 반복은 구조적 반복을 유발하는데, 이 때문에 WD repeat protein들은 공통적으로 블레이드 구조가 반복된 원형 β-propeller 구조를 형성한다 (Smith et al., 1999).

β-propeller 구조는 central pore를 기준으로 원형으로 배열된 structure module로 이루어진 구조이다. 일반적으로 각 블레이드는 4개의 antiparallel β-sheet으로 이루어져 있다. 이 구조는 4개의 잠재적인 상호작용 표면을 제공할 수 있으며, 각각 위, 아래, 둘레 그리고 깔때기 모양의 central pore(또는 central channel)에 해당한다 (Chen et al., 2011; Schapira et al., 2017; Smith et al., 1999; Stirnimann et al., 2010). 이 상호작용 표면들 중 central pore는 단백질들과 상호작용 하기에는 너무 좁기 때문에 잠재적인 상호작용 표면으로 간주하지 않았으나 (Smith et al., 1999), central pore 혹은 그 진입부위가 주요 상호작용 partner의 peptide 혹은 저분자와 상호작용을 하기에 적절한 크기와 물리화학적 특징을 가지고 있고 상호작용을 자주 매개한다고 알려져 있다 (Schapira et al., 2017; Stirnimann et al., 2010).

WD40 domain의 구조적 보존성에 비해서 서열 보존성은 낮다. 공개된 구조 정보들에 따르면 대부분의 WD repeat protein들은 7개(또는 7의 배수)의 blade를 포함하고 있는 β-propeller 구조이다. 하지만 몇몇 WD repeat protein의 경우 서열 기반의 분류를 사용하는 Uniprot에서는 6회 미만의 WD repeat을 포함하고 있다고 annotation되어 있다는 것이 그 증거이다. 이는 WD40 domain의 서열이 대부분 특정 정규식(regular expression)을 따르고 있더라도 서열 보존성은 낮은 편이기 때문에, 실제보다 WD40 도메인의 annotation을 보수적으로 해서 나타나는 현상이다 (Stirnimann et al., 2010).

WD40 domain이 가지는 특징 때문에 WD repeat protein은 다른 단백질들과 상호작용하고 여러 기능을 갖기에 용이하다. β-propeller 구조이기 때문에 가지는 다수의 잠재적 interaction surface 때문에 여러 단백질과 interaction 할 수 있고, 구조 유지를 위해서 높은 수준의 서열보존을 요구하지 않기 때문에 기능적 다양성을 갖는다. 이 때문에 WD repeat protein은 global protein interaction network에서 중요한 역할을 한다 (Schapira et al., 2017).

[[Saccharomyces cerevisiae]]의 [[Swd2]]는 6개의 WD40 domain을 포함한 WD repeat superfamily의 하위 그룹에 속한 단백질이다 (Cheng et al., 2004). WD domain은 각각 blade 구조를 만들고, 이외의 WD domain으로 이루어지지 않은 한 개의 blade를 포함해 모여 7-bladed β-propeller 구조를 형성한다. 이때 N 말단과 C 말단이 서로 겹쳐져 Velcro snap을 만든다 (Smith et al., 1999). [[Swd2]]는 Cyro-EM 또는 NMR를 통해 직접적으로 구조가 분석되지는 않았지만 서열 기반의 예측(Dichtl et al., 2004)과 Alphafold2에 의해서 구조가 예측된 바 있고(Jumper et al., 2021; Varadi et al., 2022), 구조 예측 결과는 알려져 있는 WD repeat protein의 일반적인 구조와 일치한다.

## Swd2 기능

### Swd2 in H2Bub-H3K4me Crosstalk

H2B의 123번째 lysine residue에 monoubiquitylation이 일어나는 것은 [[Saccharomyces cerevisiae]]의 유일한 H3K4 methyltransferase인 [[COMPASS]]의 활성에 필요하다. H2BK123의 ubiquitylation을 담당하는 Bre1과 Rad6가 없으면 H3K4 di- 그리고 trimethylation이 일어나지 않거나 감지되지 않는다. Rad6가 없을 때, 정제된 [[COMPASS]]에 있는 [[Swd2]]의 양이 현저히 감소하는 것으로 보아, 이는 H2Bub가 없을 때 [[COMPASS]]에 [[Swd2]]가 tight하게 결합하지 못하기 때문이다. 이는 H2B의 monoubiquitylation을 막기 위해서 123번째 lysine을 arginine으로 치환해준 결과에서도 동일하게 나타났다 (Lee et al., 2007). 이것이 의미하는 것은 H3K4 methylation의 H2B monoubiquitylation 의존성이 [[COMPASS]]가 정상적인 활성을 갖기 위한 [[Swd2]]의 모집이 H2Bub를 요구하기 때문이라는 것이다.

H2Bub가 [[Swd2]]의 68, 69번째 lysine 잔기의 ubiquitylation을 촉진하며 이 과정에 Rad6/Bre1이 참여한다. Ubiquitylation을 막아도 [[Swd2]]와 [[Set1]] 또는 chromatin과의 interaction은 영향받지 않는다. 그러나 [[Swd2]]의 68, 69번째 lysine 잔기의 돌연변이는 5’ end에 di- 그리고 trimethylation의 감소를 유발했다. 이 효과는 [[Swd2]]의 ubiquitylation이 [[COMPASS]]의 subunit인 Spp1의 recruit을 제어하기 때문이다. 이는 [[Swd2]]가 H2Bub와 H3K4me 간의 crosstalk에서 중요한 매개자로서 활동한다는 것을 의미한다. 또한 [[Swd2]]는 [[COMPASS]]의 주요 H3 binding component이다. _(Vitaliano-Prunier et al. 2008)_

그러나 Kim et al의 2013년 연구에 따르면, [[Swd2]]를 제외한 재조합 [[COMPASS]]에서 오히려 더 강한 H2Bub dependent한 HMT 활성을 보였다. 이는 [[Swd2]]가 H2B dependent H3K4 methylation에 필연적으로 작용하지 않는다는 것을 의미한다. in vitro에 이들을 조절하는 인자가 빠진 것이 이전 연구결과와 상반된 결과가 나타난 이유일 수 있다 (Kim et al., 2013; Soares & Buratowski, 2013). In vivo에서 [[Swd2]]가 APT, [[COMPASS]]의 구조적 무결성과 두 complex 사이의 길항작용에서 하는 역할을 고려해 보았을 때, [[Swd2]]의 정확한 역할은 재평가가 필요할 것으로 보인다 (Dichtl et al., 2004; Kim et al., 2013; Nedea et al., 2008; Soares & Buratowski, 2012).

### Set1 N-terminal domain interact with Pol2 CTD thru Swd2

[[Set1]]은 N-terminal region을 통해서 Pol2의 [[C-terminal domain]]과 interaction한다. 특히 236번째 아미노산 서열에 해당하는 부분 까지가 full length [[Set1]]의 Pol2와의 interaction에서 중요한 역할을 맡는 것으로 보인다. 이 둘의 interaction에 [[Swd2]]가 참여하며, [[Swd2]]가 없을 경우 둘의 interaction은 약해진다. [[Set1]]의 말단으로부터 200개의 아미노산 서열을 truncation하면 [[Swd2]]가 둘의 interaction에 참여하지 못하고, 그에 따라서 [[COMPASS]]의 작용으로 인한 H3K4 methylation pattern은 변화하고, bulk H3K4 di-, trimethylation도 감소한다 (Bae et al., 2020). 이 결과는 [[Swd2]]의 mammalian homologue인 WDR82가 Pol2 S5P [[C-terminal domain|CTD]]에 직접 결합할 수 있으며, Setd1A의 N-terminal region과도 직접 결합할 수 있다는 연구결과와 일치한다 (Lee & Skalnik, 2008). [[Set1]] N-terminal region을 Nrd1 C-terminal interaction domain([[CTD interaction domain|CID]])으로 치환해서 [[Set1]]과 Pol2 [[C-terminal domain|CTD]]의 interaction을 부분적으로 회복시키거나 Pol2와 [[Set1]]을 fusion하면, [[COMPASS]]의 methylation 능력이 부분적으로 회복된다 (Bae et al., 2020; Soares et al., 2017). 이것은 [[Swd2]]가 [[Set1]]과 Pol2의 interaction을 매개하고, 이것이 [[COMPASS]]의 methylation 능력에 중요한 요소 중 하나라는 것을 보여준다. 흥미로운 점은, [[Swd2]]가 [[Set1]] N-terminal region과 Pol2 [[C-terminal domain|CTD]]와의 interaction을 매개하고 있고 이 부분을 Pol2와 [[Set1]]을 fusion하는 것으로 보완해도 H3K4 methylation이 H2Bub에 의존적이라는 점은 변하지 않았다는 것이다 (Bae et al., 2020; Soares et al., 2017).

## APT

APT는 Pta1, [[REF2|Ref2]], Pti1, [[Swd2]], [[Swd2]], [[Glc7]] 그리고 Ssu72(독립적인 complex로서 기능할 때는 Syc1을 포함한다. (Lidschreiber et al., 2018))[[Cleavage and Polyadenylation Factor|CPF]]라는 거대 complex에 속한 subcomplex이다. APT complex는 RNA transcription termination, 특히 snoRNA termination에서 중요한 역할을 수행한다. APT complex의 [[Glc7]]을 잃어서 나타나는 기능이상은 _[[Saccharomyces cerevisiae]]_ 의 essential gene인 snoRNA, snR13-TRS31의 termination defect를 일으켜 균주의 생존에 영향을 미친다. [[Swd2]]와 [[REF2|Ref2]]가 없을 때, [[Glc7]]이 APT subcomplex로부터 해리(dissociation)되기 때문에 동일한 현상이 일어난다. 다르게 말하면, [[Swd2]]와 [[REF2|Ref2]]가 APT complex의 무결성(integrity)을 유지해주기 때문에 Yeast에 essential하다. [[Swd2]]가 없을 때, [[REF2|Ref2]]를 과발현 시키면 dswd2의 lethality를 우회할 수 있다(Cheng et al., 2004; Nedea et al., 2008). 또한 Helicase 활성이 없는 Sen1(202) 단편을 과발현 하는 것으로도 dswd2의 lethality를 억제할 수 있지만, 이것은 APT의 기능을 복구하기 보다는 기능이상으로 인한 결과물을 극복하는 방법으로써 효과가 있다(Nedea et al., 2008).

### Swd2 distribution and Swd2-mediated COMPASS-APT crosstalk

#### distribution

Swd2는 다른 COMPASS subunit과는 다르게 유전자의 upstream 뿐만 아니라 downstream에도 peak을 가진다. 게다가 COMPASS의 platform인 Set1을 결실 시키면 다른 모든 [[COMPASS]] subunit은 제거되지만, [[Swd2]]는 downstream에 여전히 남아있는 모습을 보인다. 두가지 설명이 가능한데, 첫번째는 남아있는 Swd2가 [[COMPASS]]와 관계없이 APT에 남아있는 [[Swd2]]일 수 있고, [[COMPASS]]에 모집되기 전에 H2Bub와 독립적으로 상호작용하고 있던 [[Swd2]]가 감지되었을 수 있다. Rad6가 없는 균주에서는 H3K4 monomethylation이 여전히 남아있기는 하지만 [[Set1]]과 [[Swd2]]가 유전자 위에서 거의 발견되지 않는다 (Soares & Buratowski, 2012).

#### [[Swd2]]-mediated [[COMPASS]]-APT crosstalk

dset1 또는 drad6 균주에서 [[Swd2]]의 cross-linking이 abrogate되었음에도 불구하고 이들 균주는 [[Swd2]]가 원인인 치사성을 보이지 않는다 (Cheng et al., 2004). [[Set1]]과 Swd2가 모두 결실되었을 때 균주가 생존 가능하다는 것은 Set1의 존재가 Swd2의 필수성을 만든다는 것을 의미한다. Swd2만 고갈시켰을 때보다 둘 모두를 결실 시켰을 때, Swd2로 인한 치사성의 원인이 되는 snR13-TRS31 readthrough가 개선된 것이 그 증거이다. (Soares & Buratowski, 2012)

이에 대해서 서로 배타적이지 않은 두 가설이 있는데, 첫째로 Set1 결실상황에서 증가된 Pol2 CTD의 S5P가 Nrd1-Nab3-Sen1 complex의 recruit을 개선하기 때문에 readthrough가 개선되었을 수 있다. 그리고 APT의 모집이 COMPASS가 존재할 때에만 Swd2에 의존적이라는 것이다. APT의 모집은 Swd2이 고갈되었을 때 심각하게 감소하지만 Set1이 결실되었을 때 APT는 영향을 받지 않는다. 주목할만한 점은, 이 둘([[Swd2]]와 [[Set1]])이 모두 고갈되면 [[REF2|Ref2]]의 모집은 거의 정상이다. 이 결과는 APT의 모집을 방해하는 COMPASS의 길항기능을 Swd2가 상쇄하는 것을 나타낸다. 이 모델은 Ref2 과발현으로 Swd2의 고갈로 인한 lethality를 우회할 수 있다는 결과와 일치한다 (Nedea et al., 2008; Soares & Buratowski, 2012).

# DISCUSSION: initiation과 termination 에서의 [[Swd2]]의 기능

#### _truncated [[set1]]__의 dswd2 치사성 감소에서 착안_

[[Swd2]]는 [[Set1]] N-terminal region에 결합하며, [[Set1]]과 Pol2 [[C-terminal domain|CTD]] 사이의 interaction을 매개한다(Bae et al., 2020). [[Set1]]의 N-terminal을 잘라내면 Set1이 없을 때와 같이, Swd2로 인한 치사성을 보이지 않는다(Park & Lee, 2017; Soares & Buratowski, 2012). 이것은 Swd2로 인한 치사성이 Set1 때문이라는 Soares and Buratowski의 연구결과에서 더 나아가, Swd2의 치사성의 원인이 [[Set1]]의 N-terminal로부터 비롯된 것임을 뜻하며, [[COMPASS]]의 methylation 뿐만 아니라 APT와의 crosstalk에 관여하는 [[Swd2]]의 기능이 [[Set1]] n-terminal과 Pol2 [[C-terminal domain|CTD]]간의 interaction과 연관성이 있음을 암시한다. 심지어 [[Swd2]]와 관련 있는 APT의 subcomplex인 [[REF2|Ref2]]-[[Swd2]]-[[Glc7]]은 in vitro에서 Pol2의 core와 interaction하며, Pol2 [[C-terminal domain|CTD]]를 dephosphorylation해서 Pol2 dimerization을 유도하고 이것이 allosteric termination으로 이어질 것이라는 연구결과가 있다 (Carminati et al., 2022). 이를 바탕으로 추론해봤을 때, [[Swd2]]가 WD repeat protein이기 때문에 가지는 다면성이 유기적인 RNA transcription regulation mechanism의 전반에서 매우 중요한 역할을 하고 있음을 알 수 있다.
