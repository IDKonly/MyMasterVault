---
creation_date: 23.09.25
last_modified: 
note_type: basic
category: Swd2 review paper
memo_level: 2
aliases:
  - introduction
tags: 
Status:
  - Working
PARA:
  - Project
---
# Concept 
1. 시간순서 정리
	1. 역사적 사건을 중심으로 기술하면 읽거나 쓰는 입장에서 연구의 흐름을 정리하기 좋아보인다.  연구의 흐름을 정리하면 최근 진행되는 관련 연구에서 무엇이 중요한지 한번에 알아 볼 수 있으므로 좋다.
2. 기능적 정리 
	1. 큰것에서 작은것으로
		1. Transcription에서 부터 서술하기 시작해서 initiation과 termination, [[COMPASS]]와 [[Cleavage and Polyadenylation Factor]], 이 둘의 공통분모인 [[Swd2]]를 지목하면 [[Swd2]]의 중요성을 강조하기 좋기는 하다.
	2. 작은 것에서 큰것으로
		1. [[Swd2]]에 대한 설명을 해야 하는데 작은것에서 큰것으로 하면 종래에는 [[Swd2]]와 무관해 보이는 것을 설명해야 하니까 기능적인 부분에서 서술한다면 작은것에서 큰것으로는 좋지 않은 것 같다.

> [!example]
> # Chromological
> 일단 보류
> 
> >[!summary] Functional abstract
> >1. Transcription 
> >2. inittation - [[COMPASS]]
> >	1. methyltransferase 
> >	2. H3K4me3 is found close to transcription start sites([Lm *et al.*, 2017](zotero://select/items/@lm2017)) ([[Room_3_Lab/Shelf_1_my works/Box_0_Projects/Swd2 review paper/Inbox/Introduction|introduction]]에 있는 내용이니 레퍼런스 확인 필요
> >	3. defferent H3K4me states have distinct function
> > 		1. 이 부분은 [Lm *et al.*, 2017](zotero://select/items/@lm2017)의 [[Room_3_Lab/Shelf_1_my works/Box_0_Projects/Swd2 review paper/Inbox/Introduction|introduction]] 부분을 많이 참고하면 될 거 같다.
> >3. terminaiton -APT subcomplex of [[Cleavage and Polyadenylation Factor]]
> >4. [[Swd2]] 
> >5. simple conclusion



- 단일 단백질로서의 소개
1. 구조적 특징
	1. WD repeat
2. 대략적인 기능설명
	1. [[Swd2]]와 전사조절 ([[Swd2]]가 Transcription에 미치는 영향)
3. [[Swd2]]의 연구 한계 (Lethality)

# 레퍼런스 세부정리

## Histone posttranslational modification (PTM) regulation in transcription

### [[COMPASS]] and [[Cleavage and Polyadenylation Factor]], the complex of transcription regulator include [[Swd2]]
1. Niño, C. A., Hérissant, L., Babour, A. & Dargemont, C. mRNA Nuclear Export in Yeast. Chem. Rev. 113, 8523–8545 (2013).
2. Vitaliano-Prunier, A. et al. [[H2B ubiquitylation controls the formation of export-competent mRNP]]. Mol Cell 45, 132–139 (2012).
## Structure of [[Swd2]]

### WD repeat

1. Smith, T. F., Gaitatzes, C., Saxena, K. & Neer, E. J. The WD repeat: a common architecture for diverse functions. Trends Biochem Sci 24, 181–185 (1999).
2. [Dichtl *et al.*, 2004](zotero://select/items/@dichtl2004)의 result 첫번째 단락에서 [[Swd2]]의 7중날 프로펠러 구조를 예측함. 이는 colabfold로 예측한 결과와 일치함.

#### Alphafold prediction

>[!notice] Alphafold prediction citation rules
>[AlphaFold Protein Structure Database](https://alphafold.ebi.ac.uk/entry/P36104)
>>If you make use of an AlphaFold prediction, please cite the following papers:  
[Jumper, J _et al_. Highly accurate protein structure prediction with AlphaFold. _Nature_ (2021).](https://www.nature.com/articles/s41586-021-03819-2)  
[Varadi, M _et al_. AlphaFold Protein Structure Database: massively expanding the structural coverage of protein-sequence space with high-accuracy models. _Nucleic Acids Research_ (2021).](https://academic.oup.com/nar/advance-article/doi/10.1093/nar/gkab1061/6430488)

[Smith *et al.*, 1999](zotero://select/items/@smith1999)에서 예측한 WD repeat protein 모델과 상당히 흡사함.

자체적으로 prediction한 모델을 쓴다면..
> [!notice] Colabfold citation rules
>### [How do I reference this work?](https://github.com/sokrypton/ColabFold#how-do-i-reference-this-work)

![[Pasted image 20231005110633.png]]

## Function of [[Swd2]]
1. Nedea, E. et al. [[The Glc7 phosphatase subunit of the cleavage and polyadenylation factor is essential for transcription termination on snoRNA genes]]. Mol Cell 29, 577–587 (2008).
2. Cheng, H., He, X. & Moore, C. [[The essential WD repeat protein Swd2 has dual functions in RNA polymerase II transcription termination and lysine 4 methylation of histone H3]]. Mol Cell Biol 24, 2932–2943 (2004).
3. Park, S. & Lee, J.-S. The effect of Swd2’s binding to Set1 on the dual functions of Swd2 in Saccharomyces cerevisiae. Korean Journal of Microbiology 53, 286–291 (2017).

1. [Dichtl *et al.*, 2004](zotero://select/items/@dichtl2004) 
	1. Swd2p bridges the APT, core-CPF, and CF IA subcomplexes of the 3’ end formation machinery
	2. Swd2p is required for [[COMPASS|SET1C]] activity

### H3K4 methylation
1. Wu, M. et al. Molecular regulation of H3K4 trimethylation by Wdr82, a component of human Set1/COMPASS. Mol Cell Biol 28, 7337–7344 (2008).
2. Thornton, J. L. et al. Context dependency of Set1/COMPASS-mediated histone H3 Lys4 trimethylation. Genes Dev 28, 115–120 (2014).
3. Kim, J. et al. [[The n-SET domain of Set1 regulates H2B ubiquitylation-dependent H3K4 methylation]]. Mol Cell 49, 1121–1133 (2013).
### Histone crosstalk
1. Niño, C. A., Hérissant, L., Babour, A. & Dargemont, C. mRNA Nuclear Export in Yeast. Chem. Rev. 113, 8523–8545 (2013).
2.  Vitaliano-Prunier, A. et al. [[H2B ubiquitylation controls the formation of export-competent mRNP]]. Mol Cell 45, 132–139 (2012).
3.  Lee, J.-S., Smith, E. & Shilatifard, A. The Language of Histone Crosstalk. Cell 142, 682–685 (2010).
4. Lee, J.-S. et al. [[Histone crosstalk between H2B monoubiquitination and H3 methylation mediated by COMPASS]]. Cell 131, 1084–1096 (2007).
5. Dover, J. et al. Methylation of histone H3 by COMPASS requires ubiquitination of histone H2B by Rad6. J Biol Chem 277, 28368–28371 (2002).
6. Sun, Z.-W. & Allis, C. D. Ubiquitination of histone H2B regulates H3 methylation and gene silencing in yeast. Nature 418, 104–108 (2002).




# [[Swd2]]의 구조

## WD repeat


**WD repeat protein은 tryptophan-aspartic acid(WD)로 끝나는 WD domain이 반복된 서열을 가진 단백질을 말한다. WD domain은 약 40개에서 60개의 서열로 구성되며 잘 보존된 핵심서열을 포함하고 있다.** WD repeat은 구조적 반복을 유발하는데, 이 때문에 WD repeat protein들은 공통적으로 블레이드 구조가 반복된 원형 β-propeller 구조를 형성한다. 이 β-propeller 구조는 3개의 잠재적인 상호작용 표면(위, 아래 그리고 둘레)을 제공할 수 있다. 가운데에 있는 터널 구조는 단백질과의 상호작용을 하기에는 너무 좁기 때문에 잠재적인 상호작용 표면으로는 간주되지 않는다. (Smith et al., 1999)

WD repeat protein에는 중심에 doughnut hole 또는 central pore라고 부르는 구조를 가지고 있다. 이 구조는 상호작용 파트너의 peptide 영역과의 상호작용을 자주 매개한다. 또한 저분자에 대한 친화성을 갖기에 적절한 크기와 물리화학적 특징을 가지고 있다.
효모에서는 가장 많은 protein-protein interaction에 관여하는 도메인이며, 이는 WD repeat global protein interaction network를 연결하는 데 있어 중요한 역할을 한다는 것을 의미한다.
[Schapira *et al.*, 2017](zotero://select/items/@schapira2017)

다른 베타 프로펠러 패밀리의 멤버들과는 다르게 WD repeat protein은 효소 복합체에 존재하는 경우가 많지만 촉매 활성을 가진 WD40 단백질은 없다.

공개된 WD repeat protein들의 구조정보에 따르면 대부분의 WD40 단백질이 7개(혹은 7의 배수)의 blade를 가지고 있음에도 불구하고, sequence-based classification method를 사용하는 Uniprot에서는 종종 6회 미만의 반복을 포함하는 것으로 annotation된다.
이는 WD40 domain의 서열 보존 수준이 낮고, 기능적 다양성이 높다는 것을 의미한다.

WD40의 propeller는 300개의 아미노산으로 이루어진 도메인으로, 상호작용이 가능한 3개의 표면이 있다. 이 상호작용이 가능한 표면이란, 프로펠러의 상단영역, 하단영역, 둘레이다.

재밌는 점은 대부부분의 단백질-단백질 혹은 단백질-펩타이드 간 상호작용은 베타 프로펠러의 중앙 채널의 진입부위를 포함한다. 

WD40 도메인은 여러 단백질에 대한 대규모 상호작용플랫폼으로서 작용할 수 있다.

WD40는 효모의 interactome 분석에서 다른 어떤 종류의 domain보다도 더 많이 상호작용에 참여하나는 도메인이다.

(discussion 부분에 해당하는 내용)

WD40 도메인은 왜 자주 사용되는가?
1. 가장 간단한 가설은 많은 interaction surface를 가지고 있다는 것이다. 하지만 이건 다른 binding domain도 일치하는 이유이기 때문에 WD40만의 이유가 될 수는 없다.
2. 다른 가설은 WD domain이 다른 단백질 도메인에 비해 매우 대칭적인 구조를 갖고 있기 때문이다. 대칭적인 구조는 더 빠르고 쉬운 protein folding을 가능하게 하기 때문에, 서열이나 기능적 유사성이 낮은 단백질에 의해서 채택된 superfold일 가능성이 높다.

WD40 도메인의 베타프로펠러 구조는 구형단백질과 솔레노이드의 ‘행복한 중간체’ 일 것

WD40 domain의 다양한 기능적 특징에도 불구하고 catalytic activity가 없는 것은 아마 진화적인 시간이 모자랐을 가능성이 높다.
[Stirnimann *et al.*, 2010](zotero://select/items/@stirnimann2010)
## [[Swd2]]의 경우

WD repeat protein(혹은 WD40 protein)은 tryptophan-aspartic acid(WD)로 끝나는 WD40 domain 이 반복된 서열을 가진 단백질을 말한다. WD40 domain은 44개에서 60개의 서열로 구성되며 특정 정규식(regular expression)을 따르는 핵심서열이 존재한다 (Smith et al., 1999). WD repeat protein의 서열 반복은 구조적 반복을 유발하는데, 이 때문에 WD repeat protein들은 공통적으로 블레이드 구조가 반복된 원형 β-propeller 구조를 형성한다 (Smith et al., 1999).

β-propeller 구조는 central pore를 기준으로 원형으로 배열된 structure module로 이루어진 구조이다. 일반적으로 각 블레이드는 4개의 antiparallel β-sheet으로 이루어져 있다. 이 구조는 4개의 잠재적인 상호작용 표면을 제공할 수 있으며, 각각 위, 아래, 둘레 그리고 깔때기 모양의 central pore(또는 central channel)에 해당한다. (2011)이 상호작용 표면들 중 central pore는 단백질들과 상호작용 하기에는 너무 좁기 때문에 잠재적인 상호작용 표면으로 간주하지 않았으나 (Smith et al., 1999), central pore 혹은 그 진입부위가 주요 상호작용 partner의 peptide 혹은 저분자와 상호작용을 하기에 적절한 크기와 물리화학적 특징을 가지고 있고 상호작용을 자주 매개한다고 알려져 있다 (Schapira et al., 2017).

WD40 domain의 구조적 보존성에 비해서 서열 보존성은 낮다. 공개된 구조 정보들에 따르면 대부분의 WD repeat protein들은 7개(또는 7의 배수)의 blade를 포함하고 있는 β-propeller 구조이다. 하지만 몇몇 WD repeat protein의 경우 서열 기반의 분류를 사용하는 Uniprot에서는 6회 미만의 WD repeat을 포함하고 있다고 annotation되어 있다는 것이 그 증거이다. 이는 WD40 domain의 서열이 대부분 특정 정규식(regular expression)을 따르고 있더라도 서열 보존성은 낮은 편이기 때문에, 실제보다 WD40 도메인의 annotation을 보수적으로 했기 때문에 나타나는 현상이다 (Stirnimann, 2010).

WD40 domain이 가지는 특징 때문에 WD repeat protein은 다른 단백질들과 상호작용하고 여러 기능을 갖기에 용이하다. β-propeller 구조이기 때문에 가지는 다수의 잠재적 interaction surface 때문에 동시에 여러 단백질과 interaction 할 수 있고, 구조 유지를 위해서 높은 수준의 서열보존을 요구하지 않기 때문에 기능적 다양성을 갖는다. 이 때문에 WD repeat protein은 global protein interaction network에서 중요한 역할을 한다 (Schapira, 2017).

[[Saccharomyces cerevisiae]]의 [[Swd2]]는 6개의 WD40 domain을 포함한 WD repeat superfamily의 하위 그룹에 속한 단백질이다 (Cheng et al., 2004). WD domain은 각각 blade 구조를 만들고, 이외의 WD domain으로 이루어지지 않은 한 개의 blade를 포함해 모여 7-bladed β-propeller 구조를 형성한다. 이때 N 말단과 C 말단이 서로 겹쳐져 Velcro snap을 만든다 (Smith et al., 1999). [[Swd2]]는 Cyro-EM 또는 NMR를 통해 직접적으로 구조가 분석되지는 않았지만 Alphafold2에 의해서 구조가 예측된 바 있고(Jumper et al., 2021; Varadi et al., 2022), 구조 예측 결과는 기존에 알려진 WD repeat protein의 구조와 일치한다.

# [[Swd2]] 기능

##[[Swd2]]의 분포

Dual function (Cheng et al., 2004; Dichtl et al., 2004)

## in [[COMPASS|Set1C]]

H2ub dependent H3K4 methylation (Lee et al., 2007)

>So far, GPS has revealed that the monoubiquitination of lysine 123 of histone H2B by the Rad6/Bre1 complex (the E2/E3 enzymes) is required for histone methylation by [[COMPASS]] (Shilatifard, 2006; Wood et al., 2003a, 2003b; Dover et al., 2002; Sun and Allis, 2002).
>Indeed, this crosstalk pathway is highly conserved and is specifically required for proper H3K4 di- and trimethylation by [[COMPASS]]. In the absence of H2B monoubiquitination, the pattern of H3K4 monomethlyation is somewhat lowered but still present, however, H3K4 di- and trimethylation are not detectable (Schneider et al., 2005; Shahbazian et al., 2005).

→ H2BK123ub를 담당하는 Bre1과 Rad6가 없으면 H3K4 di- tri methylation이 일어나지 않거나 감지되지 않는다.

> Perhaps in the absence of H2B monoubiquitination, [[COMPASS]] is not held together as tightly.

→ H2Bub 없으면 [[compass]]가 타이트하게 결합하지 못한다.

> From this comprehensive study, we observed that the association of Cps35 within [[COMPASS]] is severely affected in strains bearing a single point mutation on lysine 123 of histone H2B (Figure 3).

> Our studies show not only is Cps35 required for the H3K4 methylation pattern (Figure 6B upper panel), but also that its partial loss can result in the reduction of H3K79 trimethylation levels in vivo (Figure 6B lower panel). 

→ Swd2의 존재는 H3K4의 trimethylation pattern에 필요할 뿐만 아니라, 부분적인 감소마저도 H3K72의 trimethylation 레벨을 감소시킨다. 

> It is not clear at this time whether the physical interactions between Dot1 and Cps35 require H2B monoubiquitination. 
> Future studies addressing this possibility and determining if Cps35 and Dot1 are part of a macromolecular complex or whether their interaction is transient through chromatin should shed further light on this subject.

> Our studies have demonstrated that [[Set1]] is essential for [[COMPASS]] formation, [[COMPASS]] subunit stability and H3K4 methylation (Steward et al., 2006). Therefore, we wanted to determine whether Cps35 is capable of associating with chromatin in the absence of [[COMPASS]]. As demonstrated before, chromatin is devoid of H3K4 methylation in the absence of [[Set1]] (Shilatifard, 2006)(Figure 6D). However, it appears that in the absence of [[Set1]], Cps35 stability is not altered and it is still capable of interacting with chromatin (Figures 6E and 6F). Together, our data indicate that Cps35’s interactions with chromatin in vivo is independent of [[Set1]] and requires monoubiquitinated H2B.****

[Vitaliano-Prunier *et al.*, 2008](zotero://select/items/@vitaliano-prunier2008)
[[Ubiquitylation of the COMPASS component Swd2 links H2B ubiquitylation to H3K4 trimethylation]]

Pol2 C-terminal interact. (Bae et al. 2020)

## in APT

→ Swd2의 분포와 COMPASS-APT crosstalk

>[[Swd2]]는 다른 [[COMPASS]] subunit과는 다르게 upstream 뿐만 아니라 downstream에도 peak을 가진다. 게다가 [[COMPASS]]의 platform인 [[Set1]]을 결실 시키면 다른 모든 [[COMPASS]] subunit은 제거되지만, [[Swd2]]는 downstream에 여전히 남아있는 모습을 보인다. 두가지 설명이 가능한데, 첫번째는 남아있는 [[Swd2]]가 [[COMPASS]]와 관계없이 APT에 남아있는 [[Swd2]]일 수 있고, [[COMPASS]]에 모집되기 전에 H2Bub와 독립적으로 상호작용하고 있던 [[Swd2]]가 감지되었을 수 있다. Rad6가 없는 균주에서는 H3K4 monomethylation이 여전히 남아있기는 하지만 [[Set1]]과 [[Swd2]]가 유전자 위에서 거의 발견되지 않는다 (Soares & Buratowski, 2012).

>dset1 또는 drad6 균주에서 [[Swd2]]의 cross-linking이 abrogate되었음에도 불구하고 이들 균주는 [[Swd2]]가 원인인 치사성을 보이지 않는다 (Cheng et al., 2004). [[Set1]]과 [[Swd2]]가 모두 결실되었을 때 균주가 생존 가능하다는 것은 [[Set1]]의 존재가 [[Swd2]]의 필수성을 만든다는 것을 의미한다. [[Swd2]]만 고갈시켰을 때보다 둘 모두를 결실 시켰을 때, [[Swd2]]로 인한 치사성의 원인이 되는 snR13-TRS31 readthrough가 개선된 것이 그 증거이다. (Soares & Buratowski, 2012)

>이에 대해서 서로 배타적이지 않은 두 가설이 있는데, 첫째로 [[Set1]] 결실상황에서 증가된 Pol2 [[C-terminal domain|CTD]]의 S5P가 Nrd1-Nab3-Sen1 complex의 recruit을 개선하기 때문에 readthrough가 개선되었을 수 있다. 그리고 APT의 모집이 [[COMPASS]]가 존재할 때에만 [[Swd2]]에 의존적이라는 것이다. APT의 모집은 [[Swd2]]이 고갈되었을 때 심각하게 감소하지만 [[Set1]]이 결실되었을 때 APT는 영향을 받지 않는다. 주목할만한 점은, 이 둘이 모두 고갈되면 [[REF2|Ref2]]의 모집은 거의 정상이다. 이 결과는 APT의 모집을 방해하는 [[COMPASS]]의 길항기능을 [[Swd2]]가 상쇄하는 것을 나타낸다. 이 모델은 [[REF2|Ref2]] 과발현으로 [[Swd2]]의 고갈로 인한 lethality를 우회할 수 있다는 결과와 일치한다 (Nedea et al., 2008; Soares & Buratowski, 2012)


[[Glc7 is dissociation after Swd2 depletion (Nedea et al., 2008) draft]]


APT complex distinct CPF [Lidschreiber *et al.*, 2018](zotero://select/items/@lidschreiber2018)