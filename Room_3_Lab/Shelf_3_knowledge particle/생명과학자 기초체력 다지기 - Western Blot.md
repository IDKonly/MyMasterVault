---
title: 무제 파일
creation_date: 23.03.06
last_modified: 
note_type: basic
category: 
memo_level: 
aliases: 
tags:
  - BRIC
  - 생물학연구정보센터
  - Western_blot
  - Biology
  - Methodology
source: https://www.ibric.org/myboard/read.php?Board=news&id=323152
---

Parent : [[_KnowledgeParticle]]
Drived from : [[]]

> ## Excerpt
> “생명 과학자 기초 체력 다지기” 세번째 주제는 “단백질 시료”에서 “항체”를 probe (탐침)로 사용하여 특정 “단백질의 유무”를 확인하는 방법인 “[[Western blot]] (WB)”에 대해 알아 보고자 한다.

---
**“생명 과학자 기초 체력 다지기”** 세번째 주제는 **“단백질 시료”** 에서 **“항체”** 를 probe (탐침)로 사용하여 특정 **“단백질의 유무”** 를 확인하는 방법인 **“Western blot (WB)”** 에 대해 알아보고자 한다.

**Western blot**이라는 명칭만 봐서는 무슨 실험법인지 바로 와 닿지 않는다. 그 이유는 이 명칭이  **“DNA 시료”** 에서 **“DNA”** 를 probe로 사용하여 특정 **“유전자(DNA)의 유무”** 를 확인하는 방법을 1975년 **Edwin Southern**이 개발하여 자신의 이름을 따서 **“Southern blot”** 이라 하고, 그 뒤 **“RNA 시료”** 에서 **“DNA”** 를 probe로 사용하여 유전자의 전사체인 특정 **“RNA의 유무”** 를 확인하는 방법을 **“Northern blot”** 이라 붙인 데서 비롯된 상대적인 명칭이기 때문이다.

예전엔 3종류의 실험법을 구분하는 것이 헷갈렸었는데, 지금은 Southern이나 Northern blots은 보다 간편하고 특이성이 높은 **[[PCR]]법**으로 대체되고, Western blot만 주로 사용되고 있어 그럴 일은 없을 듯하다.    
 

![The processes of Western blot](https://www.ibric.org/upload/geditor/202010/0.86240600_1603194666.png)

**Figure 1. The processes of Western blot**

  
**WB**이 비록 보편적인 실험법이긴 하지만 적용하기 위해서는 확인하고자 하는 “표적 단백질에 특이적인 항체”가 반드시 있어야 한다는 전제 조건이 있다.

**WB**은 크게 **"4단계 과정"** 으로 나눌 수 있다. 1) **시료 준비**, 2) 시료를 polyacrylamide gel에서 **전기영동**하여 분자량에 따라 분리, 3) 단백질을 gel에서 membrane으로 **[[transfer]]**, 4) 항체를 사용하여 **표적 단백질 확인**.

그럼 WB의 각 단계별 과정을 하나씩 차근차근 알아 보자.

**시료 준비 (Sample preparation)**

**첫 번째 단계는 단백질 시료를 준비하는 과정이다.**

단백질 시료는 미생물이나 동식물의 세포 혹은 조직으로부터 분리한다. 가장 일반적인 예는, 대장균이나 동물세포주에 특정 유전자를 도입하여 발현시킨 후 단백질을 추출하여 발현 유무를 확인하는 경우이다.

세포나 조직에는 다양한 단백질이 존재한다. 추출 후에는 단백질 혼합물을 전기영동으로 분리하게 되는데, 이때 각 well에 loading 할 수 있는 단백질 양이 **"제한적"** 이다. 보다 쉽게 표적 단백질을 확인하기 위해서는 단백질 추출 단계에서 표적 단백질을 **"선택적"** 으로 가능한 많이 추출하는 방법이 유리하다.

예를 들어, 표적 단백질의 위치가 세포질이면 **"세포질 단백질"** 만 추출하는 방법을, 막 단백질이라면 세포질 단백질을 먼저 제거한 후 **"막 단백질"** 을 추출한다.

이러한 선택성을 결정하는 요소가 **“detergent (계면활성제)”** 이다. **세포질 단백질**은 mild한 detergent나 기계적 (homogenizer) 혹은 물리적 (freeze-thaw)인 파쇄만으로 추출이 가능하다. 반면, **막 단백질**은 좀 더 강한 detergent를 사용하여야 효율적인 추출이 가능하다. 단백질 추출 buffer에 사용되는 **"detergent"** 로는 **NP-40, Triton X-100, Sodium dodecyl sulfate (SDS), Sodium deoxycholate**, 등이 사용된다.

  
**Table 1. Protein extraction buffers**  
![Protein extraction buffers](https://www.ibric.org/upload/geditor/202010/0.26350200_1603194798.png)

**단백질 추출 시 주의해야 할 점**은, 추출 과정에 표적 단백질이 **"변형"** 혹은 **"분해"** 되지 않도록 하여야 한다. 단백질 간의 결합을 유지하기 위해서는 **SDS**나 **Triton X-100**은 사용하지 않아야 한다. 단백질 분해를 방지하고 인산화 상태를 유지하기 위해서는 lysis buffer에 **"protease inhibitor"** 와 **"phosphatase inhibitor"** 를 반드시 사용하여야 한다.

**"Protease inhibitor"** 는 여러 가지가 혼합된 cocktail 형태를 사용한다. 다만, 추출 후 His-tag 단백질과 같이 Ni 혹은 Cu가 포함된 His-tag 정제 column을 사용하는 경우는 **[[EDTA]]**나 **EGTA**와 같은 metal chelator를 사용해서는 안 된다. 사용하면 단백질이 [[column]]의 resin에 결합하지 않는다.

**Table 2. Proteases/Phosphatases inhibitors**  
![upload_image](https://www.ibric.org/upload/geditor/202010/0.68904100_1603194912.png)

배양한 **"동물세포"** 로부터 단백질 시료를 추출하는 과정을 실례로 알아보자.

부착 세포의 경우 배지를 제거하고 PBS로 2회 정도 씻어 남은 배지 성분을 제거한다. 배양 용기를 얼음 위에 두고 lysis buffer를 첨가하여 골고루 덮이게 한 후, cell scrapper를 사용하여 세포를 긁어모아 tube에 옮겨 담는다. 세포 회수가 끝나면 **"pipetting"** 으로 cell lysate를 만드는데, 이때 pipetting 횟수를 일정하게 하여 샘플 간 차이가 없도록 한다.

**"RIPA buffer"** 를 사용하면 **"chromosomal DNA"** 가 유리되어 끈적하게 되는데, pipetting을 **"30~50회"** 정도 반복하면 chromosomal DNA가 pipet tip을 통과하면서 잘게 잘라져 끈적임이 없게 된다. 이 단계에서 pipetting이 충분하지 않으면 끈적임 때문에 시료 회수가 어려울 뿐 아니라, 전기영동 시 **"smear"** 하게 끌리는 현상이 발생한다. Lysate는 원심분리 (12,000 rpm, 5 min)하여 상층액만 회수한 후, **BCA**와 같은 방법 ([https://en.wikipedia.org/wiki/Bicinchoninic\_acid\_assay](https://en.wikipedia.org/wiki/Bicinchoninic_acid_assay))으로 단백질을 정량한다.

**Table 3. Protein quantification methods**  
![ Protein quantification methods](https://www.ibric.org/upload/geditor/202010/0.98066700_1603194991.png)

정량값과 시료의 부피를 측정한 후 단백질의 농도가 "**가장 낮은 것"** 을 기준으로 lysis buffer를 사용하여 계산하기 편한 "**동일 농도"** 로 모두 맞춘다. 연재 1회에서 소개한 "**C<sub>1</sub>V<sub>1</sub>\=C<sub>2</sub>V<sub>2"&nbsp;</sub>** 식에 따라 농도를 맞춘다.

미니 gel (10 cm x 10 cm 이내)의 경우, 각 well에 사용 가능한 시료의 부피는 **50 μL 이내**, 단백질의 양은 **30 μg 이내**로 사용한다.

예를 들어, 각 well별로 30 μL를 사용하고, 2x Sample buffer를 사용한다면, 사용 가능한 시료의 부피는 15 μL가 된다. 30 μg의 시료를 사용하고자 한다면, 시료의 농도는 **최소 2 μg/μL**가 되어야 한다. 배양한 세포에서 추출되는 개략적인 단백질의 농도를 알고 있다면, 사용하는 **"lysis buffer의 양을 조절"** 하여 lysate의 단백질 농도가 최소 요구 농도 이상이 되도록 하여야 한다.

**전기영동 (Electrophoresis)**

**두 번째 단계는**, **polyacrylamide gel 에서 단백질 혼합물을 "전기영동"하여 분자량에 따라 분리하는 과정이다.**

**"Polyacrylamide"** 는 acrylamide와 bisacrylamide의 중합체로, 단백질 시료를 분자량에 따라 분리하는 **"분자 체 (molecular sieve)"** 역할을 한다. 분자 체의 크기는 주요 building block인 acrylamide와 가교 (cross-linker) 역할을 하는 bisacrylamide의 전체 농도와 혼합 비율에 따라 조절된다.

여기서 두 가지 농도 개념이 사용되는데, **“%T (Total)”** 는 acrylamide와 bisacrylamide를 합친 전체 농도를 나타내고, **“%C (cross-linker)”** 는 전체 농도에서 cross-linker인 bisacrylamide의 농도를 나타낸다.  
 

![ Western Blot](https://www.ibric.org/upload/geditor/202010/0.07769700_1603195026.png)

  **%T**가 증가할수록 분자 체의 pore size는 비례해서 작아지며, **5~25%** 범위 내에서 사용된다.

**%C**는 **"5%"** 까지는 농도가 증가할수록 pore size가 작아지지만, 5% 이상이면 cross-linker끼리의 결합으로 오히려 pore size가 커진다.

그 이유는 5%까지는 bisacrylamide (bis)가 acrylamide(A)간의 가교 역할 **"(A-bis-A)"** 만 하지만, 그 이상 농도에서는 bisacrylamide간의 결합 **"(A-bis-bis-A)"** 이 형성되어 acrylamide간의 간격이 증가하면서 pore size는 오히려 **커지게** 된다.

**"Acrylamide와 bisacrylamide의 비"** 는 **단백질**의 경우 **29:1 (3.3%C)** 을 주로 사용하고, 분자량이 작은 **peptide**는 **19:1 (5%C)** 을 사용한다.

일반적으로 사용하는 **“Discontinuous gel”** 은 **4.5%** 의 **"stacking (or concentration) gel"** 과 **8~20%** 농도 범위의 **"separation gel"** 을 사용한다.

**"Stacking gel"** 은 각 well에 넓게 퍼져 있는 단백질 시료를 압축하여 separation gel에서는 거의 동일선상에서 출발하도록 하며, 분자량에 따라 분리는 separation gel에서 일어난다.

**“Gradient (continuous) gel”** 은 별도의 stacking gel 없이 gel 농도를 **5~15%** 까지 연속적인 gradient로 만든 것이다. 낮은 농도에서는 샘플의 압축이 일어나고, 높은 농도에서는 분자량에 따른 분리가 일어난다. 분자량에 따른 분리도가 단일 농도의 discontinuous gel에 비해 우수하다. 

**Table 4. Recommended gel concentration by protein size**  
![Recommended gel concentration by protein size](https://www.ibric.org/upload/geditor/202010/0.77806900_1603195069.png)

Acrylamide와 bisacrylamide간의 중합 반응이 일어나기 위해서는 **"Ammonium persulfate (APS)와 TEMED"**, 두 가지 시약이 필요하다.

**"APS"** 는 분자간의 결합에 필요한 **free radicals을 제공**하고 cross-linking을 촉진하며, **"TEMED"** 는 free radical 생성을 촉매하여 **중합 반응을 개시**하는 역할을 한다.

**APS**는 항상 **fresh**하게 만들어 사용해야 한다. 조제하지 않은 시약은 유효기간이 지나도 괜찮다고 생각하기 쉬운데, APS는 유효기간이 지난 정도에 따라 중합 반응이 전혀 일어나지 않을 수 있다. 따라서, 시약은 반드시 유효기간 이내의 것만 사용해야 한다.

**TEMED**는 APS와 함께 **중합 반응의 개시**와 속도를 결정한다. 농도가 높아질수록 중합 반응 속도도 빨라진다. 건설 공사도 너무 빨리 하면 날림 공사가 되는 것처럼, 중합 반응도 적정 속도가 필요하다.

요즘은 실험실 환경이 적정 온도를 유지하여 문제가 없지만, 예전에는 여름철에는 실내 온도가 높아 중합 반응이 너무 빠르고, 겨울철에는 중합 반응이 느려 TEMED 농도를 조절하여 사용하기도 했다. 1회용 pre-casting gel을 사용하는 경우가 많아 gel 만드는 과정이 생략되는 경우가 많지만, gel이 만들어지는 원리는 알 필요가 있다.

**"Polyacrylamide gel electrophoresis (PAGE)"** 는 단백질 시료의 고차 구조가 유지되는 **"native PAGE"** 와 변성된 단백질을 사용하는 **"denaturing 또는 [[SDS-PAGE]]"** 로 구분된다.

**“Native PAGE”** 는 gel과 sample 조제 시 고차 구조를 변성(subunit 분리)시키는 SDS (Sodium dodecyl sulfate)나 S-S 결합을 분리시키는 reducing agent를 사용하지 않는다.

**“[[SDS-PAGE]]”** 는 SDS를 gel과 sample buffer에 사용하고, reducing agent (2-mercaptoethanol, 5~20 mM; Dithiothreitol(DTT), 0.5~1 mM)를 sample buffer 에 사용한다.

**"SDS"** 는 단백질 1 g당 약 **1.4 g**이 결합되는데, 이는 단백질 전체를 **"(-) charge"** 가 되도록 코팅하는 역할을 하며, 전기영동 시 단백질의 구조나 charge에는 영향을 받지 않고 오로지 **분자량에 의해서만 분리**되도록 한다.

전기영동 샘플 조제는 **2x Sample loading buffe**r와 1:1로 섞은 후 **100°C**에서 **5분**간 끓여 준비한다. 단백질 샘플의 농도가 낮다면, 5x Sample loading buffer를 사용하여 샘플의 양을 증가시키면 된다.  Eppendorf tube에 샘플을 넣고 그냥 끓이면 압력으로 뚜껑이 갑자기 열리면서 샘플을 소실할 수 있다. PCR 기기가 있다면, **95°C**에서 **5분**간 열변성시키는 것으로 대체 가능하다.

미니 gel에 사용하는 각 well별 샘플의 양은, **cell lysate**는 **20~30 μg** 정도, **정제한 단백질**은 **10~100 ng** 정도를 사용한다. Gel에서 comb을 제거하고 샘플을 loading 하기 전 각 well에 중합되지 않고 남아 있는 acrylamide를 running buffer로 pipetting하여 씻어 내어야 sample이 깔끔하게 loading된다. 

**Table 5. SDS-PAGE buffers**  
![SDS-PAGE buffers](https://www.ibric.org/upload/geditor/202010/0.07849600_1603195102.png)

단백질의 분자량을 확인하기 위한 **"분자량 마커"** 는 prestained marker와 unstained marker가 있다.

**"Prestained marker"** 는 단백질이 gel상에서 분리되면서 바로 관찰이 가능하지만 염색 dye 결합으로 동일한 단백질의 unstained marker와는 이동 속도가 **다르다**. Prestained marker는 동일한 단백질이라도 dye 결합 정도가 다른데, batch별 calibration한 값을 제대로 제공하지 않아 회사별로 **"제각각"** 인 경우가 있다. 보다 정확한 분자량 확인을 위해서는 unstained marker와 비교하여 분자량이 제대로 나오는 것을 선별하여 사용할 필요가 있다.

Sample buffer에는 **"bromophenol blue (BPB)"** 가 포함되어 있다. BPB의 분자량은 670 Da으로, 단백질보다 훨씬 작아 가장 **선단**에서 이동하여 전기 영동의 진행 정도를 파악하는 **"indicator"** 역할을 한다.

전기영동용 power supply는 **전류, 전압**, 혹은 **전력** 값을 일정하게 설정할 수 있다. 단백질의 분리 효율을 높이기 위해서는 이동 속도를 **일정하게** 유지하는 것이 필요하다. 단백질 이동 속도는 전압에 비례하기 때문에 **“constant voltage”** 를 사용한다. Stacking gel에서는 **80 V**, separation gel에서는 **100~120 V**를 사용한다.

전기영동 시 전압과 전류가 어떻게 영향을 미치는지 잠깐 알아보고 가자.

**“전압(V) = 전류(A) x 저항(R)”** 식에서 알 수 있듯이, **“constant voltage”** 조건에서는 전기 영동이 진행됨에 따라 gel 속의 이온 농도가 낮아져 저항(R) 값이 증가하게 되는데, 일정한 전압 (V)을 유지하기 위해 전류 (A) 값은 감소된다.

반면, **“constant ampere”** 조건 (**“전류(A) = 전압(V)/저항(R)”**)에서는 전기 영동이 진행됨에 따라 저항(R) 값이 증가하면 일정한 전류(A) 값을 유지하기 위해 전압(V)이 같이 증가된다. 즉, 시간이 지남에 따라 전기 영동의 속도가 빨라져 일정한 속도가 유지되지 않는다. 뿐만 아니라, constant ampere 조건에서는 시간이 지남에 따라 전압(V)이 계속 증가하여, **“전력(W) = 전류(A) x 전압(V)”** 식에 따라 전력(W), 즉, **열 발생**이 증가한다. 열이 발생하면 gel의 pore size에도 악영향을 주어 전기 영동의 해상도를 감소시키는 원인이 된다.

따라서, 전기영동은 **"constant voltage"** 조건을 사용한다.

**샘플 전송 (Transfer)**

**세 번째 단계는 acrylamide gel에서 분리한 "단백질을 membrane으로 transfer(전송)하는 과정"이다.**

Transfer는 **“Wet (tank) transfer”** 와 **“Semi-dry transfer”** 로 나뉜다.

**"Wet transfer"** 는 일반적인 전기영동 tank에 transfer buffer (25 mM Tris, 192 mM Glycine, pH8.3, 20% methanol)를 채우고, transfer cassette이 buffer에 잠긴 상태로 전송하는 방법이다. 이 경우 transfer하는 동안 온도 조절이 가능하여 보다 좋은 결과를 얻을 수 있는 반면, 보다 긴 시간과 많은 transfer buffer가 소모된다.

**"Semi-dry transfer"** 는 semi-dry transfer 장치를 사용하여 보다 적은 transfer buffer를 사용하여 보다 짧은 시간에 효율적인 transfer가 가능하지만, 온도 조절이 되지 않아 background가 증가될 수 있다.

**"Wet transfer"** 는 low abundance protein 분석에, **"semi-dray transfer"** 는 high abundance protein 분석에 추천된다. 두 가지 방법 모두 2개 이상의 gel을 transfer할 경우 위치에 따라 효율이 **달라진다**. Wet transfer는 (+)극 쪽의 gel transfer 효율이 좋고, semi-dry transfer는 plate의 중앙보다는 전극 쪽의 transfer 효율이 좋은 경향을 보인다. 2개 이상의 gel을 transfer할 경우, transfer가 잘 되는 위치에 abundance가 낮은 단백질 분석용 gel 두는 것이 좋다.

Transfer에는 **"Nitrocellulose (NC)"** 와 **"Polyvinylidene difluoride (PVDF)"** 두 종류의 membrane이 사용된다.

**"PVDF membrane"** 은 **methanol**에 약 **15초** 정도 적셔 **(+) charged group을 활성화**시키는 전처리 과정이 필요하고, 모든 과정에 membrane을 마르지 않게 유지해야 된다는 점을 제외하고, 단백질 결합 용량이 크고, 물리화학적 특성이 우수하다는 장점이 있다. 또 표적 단백질의 크기에 따라 pore size를 선택할 수 있다. 분자량이 **20 kDa 이하**인 경우는 **0.22 μm**, 그 이상의 경우는 **0.45 μm**를 사용한다. 

**Table 6. Membrane types for Western blot**

![Membrane types for Western blot](https://www.ibric.org/upload/geditor/202010/0.39056700_1603195137.png)

**"Transfer cassette assembly"** 는 wet transfer 기준이며, **"(+)극/Sponge pad/Filter paper(2~3매)/Membrane/Gel/Filter paper(2~3매)/Sponge pad/(-)극"** 순으로 차례로 겹쳐 조립하게 된다. 이 부분은 bubble이 갇히지 않게 잘 조립하는 것이 매우 중요하므로 좀 더 자세히 설명하고자 한다.

Ice block을 사용하는 경우, WB 하루 전에 냉동실에 미리 얼려 둔다. 전기 영동이 끝날 때쯤 transfer 준비를 시작한다. **"Sponge와 filter paper"** 는 transfer buffer에 미리 충분히 적셔 bubble을 제거한 후 사용한다. 건조된 sponge pad는 잘 젖지 않는데, 70% alcohol sprayer를 사용하여 적신 후 흐르는 수돗물로 완전히 적신다. 물기를 틀어서 완전히 제거하고 transfer buffer에 담가 준비한다. Filter paper도 마찬가지로 transfer buffer에 한쪽 면부터 시작하여 전체를 담가 준비한다.

전기 영동이 끝나면 transfer buffer를 넣은 별도의 용기에 gel을 분리하여 **"잠시"** 담가 둔다.

먼저, **"Transfer cassette"** 이 완전히 잠길 수 있는 크기의 사각형의 유리 혹은 stainless tray를 준비한다. 여기에 transfer cassette을 담갔을 때 **(+)극 쪽 filter paper가 잠기지 않을 정도**로만 transfer buffer를 채운다. 너무 적으면 gel을 잘못 올려 놓았을 때 움직이기 힘들고, 너무 많으면 gel이 떠 버리기 때문이다.

빈 cassette의 **(+)극** 쪽이 바닥 쪽으로 향하도록 둔다. Transfer buffer에 충분히 적신 **"sponge pad"** 를 놓고, **"filter paper"** 를 1장씩 차례로 2장을 겹쳐 놓는다. 그 위에 **"membrane"** 을 bubble 갇히지 않게 조심하면서 올려 놓는다. Filter paper와 membrane 사이에 bubble이 있다면 **"roller나 pipet"** 을 사용하여 완전히 제거한다.

그다음이 gel을 membrane 위에 올려 과정인데, 이때 **"bubble이 사이에 갇히지 않게 하는 것이 가장 중요"** 하다.

Membrane 위에 buffer가 없다면 pipette을 사용하여 **"충분히"** 적셔 준다. 앞서 transfer buffer에 잠시 담가 둔 gel은 가볍게 씻어 SDS에 의한 bubble이 gel에 묻어오지않게하면서 gel의 양쪽을 두 손으로 조심스럽게 잡고, 양손으로 잡은 gel의 **"가운데 부분"**이 먼저 membrane에 닫게 한 후, 양손으로 잡은 쪽을 서서히 내려놓아 bubble이 갇히지 않게 한다.

이 때 **"한 번에"** bubble이 갇히지 않게 겹쳐 놓는 것이 중요하다. Gel을 겹쳐 놓는 순간 단백질이 membrane에 붙을 수 있기 때문에 한 번에 올려놓고 움직이지 않는 것이 좋다. 앞서 transfer buffer를 membrane 위에 올려 두었기 때문에 gel이 완전히 밀착된 것은 아니다.

큰 bubble이 갇혔다면 gel을 다시 들었다 겹쳐 놓는 것이 좋고, 작은 bubble은 roller를 사용하여 gel의 **"가운데 쪽에서 바깥쪽으로"** 밀어 bubble을 제거해 준다. Bubble이 없더라도 roller로 전체를 밀어 주어 membrane과 gel 사이의 buffer가 제거되어 밀착되도록 한다.

Assembly를 **"(+)극 쪽에서 시작하는 이유"** 는 membrane에 gel을 올려놓았을 때 gel이 투명하여 **bubble이 쉽게 관찰**되기 때문이다. 반대로 (-)극 쪽에서 시작하면 gel 위에 membrane을 올려놓아야 하므로 bubble을 관찰할 수 없다.

그다음은 filter paper를 1장씩 차례로 2장을 겹쳐 놓고 그 위에 sponge pad를 마지막으로 올려놓는다. 이때 각 step 사이에 roller를 사용하여 bubble이 갇히지 않게 제거하는 과정이 포함된다.

일단 assembly가 끝난 cassette은 membrane과 gel이 서로 밀리지 않게 **"움직임을 최소화"** 해야 한다.

Gel과 membrane 사이에 bubble이 갇히면, 부분적으로 전기가 흐르지 않아 bubble 바깥쪽으로 transfer가 일어난다. 

![Western blot assembly](https://www.ibric.org/upload/geditor/202010/0.06888600_1603195178.png)

**Figure 2. Western blot assembly**

표적 단백질의 크기에 따라 전기영동이나 transfer 조건을 최적화하는 것이 필요하다.

분자량이 **15 kDa 보다 작은 경우**, cross-linker 농도를 **5%** 로 사용한 15% gel을 사용하고, Tris-Glycine buffer 대신 **"Tris-Tricine buffer"** 를 사용하여 **60~80V**로 전기영동 할 것을 추천한다. Transfer에는 **0.22 um** PVDF membrane을 사용하고, transfer time도 보다 **짧게** 하는 것이 필요하다.

분자량이 **15 kDa 보다 클 경우**, cross-linker 농도를 줄인 **5~8%** gel을 사용하고, transfer는 전류량을 높여 **4°C**에서 **overnight**로 하는 것이 필요하다.

**"표준 transfer buffer (Towbin buffer)"** 의 조성은 25 mM Tris, 192 mM Glycine, pH8.3, 20% Methanol이다. **분자량이 큰 경우**는 transfer buffer에 사용하는 **methanol** 농도는 **10%** 로 줄이고, **SDS**를 0.1~0.25%까지 추가하기도 한다. **"Methanol"** 은 SDS를 제거하고 gel의 pore size를 작게 하여 큰 단백질의 **transfer 효율을 감소**시킨다.

**"Transfer 시간"** 은 표적 단백질의 크기에 따라 조정이 가능한데, **"Wet transfer"** 는 **60~120 min**, **"Semi-dry transfer"** 는 **~10 min** 정도 소요된다.

Transfer가 끝나면, membrane은 **"Ponceau S 염색액 (0.1% Ponceau S, 5% acetic acid)"** 을 사용하여 **"일시적으로"** 염색이 단백질 band 확인이 가능하다. Ponceau S는 확인 후 물이나 PBS로 **제거가 가능**하다. Transfer 효율을 최적화할 경우 transfer가 끝난 gel도 Coomassie로 염색하여 단백질 잔류 여부를 확인한다.

**표적 단백질 검출 (Detection)**

**네 번째 단계는, "항체를 사용하여 표적 단백질을 검출"하는 과정이다.**

**"검출 과정"** 은 **blocking, primary antibody binding, secondary antibody binding, detection**으로 구성되어 있다. 각 step 간에는 washing 단계가 추가된다.

Gel에서 단백질을 transfer한 상태의 membrane은 단백질이 결합한 자리 이외의 부분은 다른 어떠한 단백질도 비선택적으로 결합이 가능하다. 따라서, membrane에서 단백질이 결합한 자리 이외의 모든 부분은 다른 단백질을 결합시켜 그다음 step에 사용할 항체와 같은 단백질이 결합할 수 없도록 하여야 한다.

**"Blocking"** 은 **BSA, Skim milk, Gelatin, Casein, Serum** 등을 사용하여 membrane에 존재하는 단백질 결합 site를 masking하여 비 특이적인 결합이 일어나지 않도록 하는 과정이다.

샘플의 종류나 표적 단백질에 따라 적합한 blocking buffer를 선택하여 사용하여야 한다. 일반적으로는 **"skim milk"** 와 **"BSA"** 를 가장 많이 사용한다. 다만, **"인산화된 (phosphorylated) 표적 단백질"** 에 대해서는 background를 줄이기 위해 skim milk나 casein 대신 **"5% BSA"** 를 사용하고, buffer도 TBST가 아닌 **"PBST"** 사용을 추천한다. Blocking 시간은 실온에서는 **1시간** 정도면 충분하다.

**Table 7. Membrane blocking buffers for Western blot**

![Membrane blocking buffers for Western blot](https://www.ibric.org/upload/geditor/202010/0.22216700_1603195226.png)

Blocking 다음 단계는 표적 단백질에 특이적인 **"primary antibody을 표적 단백질에 결합"** 시키는 과정이다.

**"Primary antibody"** 는 표적 단백질에 대한 **특이성**이 가장 중요하다. 항체는 항원의 형태나 종류, 제작 방법에 따라 인식하는 항원의 종류도 달라지므로 실험 목적에 부합하는 항체를 사용하여야 한다. WB에 사용되는 primary 항체를 선택할 때는 정제된 단백질이 아닌 cell lysate를 사용하여 특이성이 검증되고 이미지를 제공하는 항체를 사용할 것을 추천한다. **"Primary 항체"** 는 **mouse, rat, rabbit 유래**가 주로 사용된다.

Primary 항체의 희석에는 blocking buffer를 사용하며, sample gradient dot blot을 사용하여 최적의 희석 농도를 결정한다. 적절하게 희석된 primary 항체를 사용하여 **4°C**에서 **overnight** 동안 반응시킨다.

Primary 항체와의 반응이 완료되면 PBST 혹은 TBST를 사용하여 washing을 **실온**에서 **10분간 3회** 반복한다.

이때 membrane이 washing tray 바닥에 달라붙지 않게 **충분한** 양의 washing buffer를 사용하여 orbital shaker 혹은 rocker를 사용하여 shaking하면서 washing한다. 간혹 너무 적은 양의 washing buffer를 사용하여 shaking이 충분하지 않으면 membrane 중앙 전체에 "**background"** 가 심하게 나타나는 경우가 있다. 

**"Secondary 항체"** 는 제조사의 매뉴얼에 따라 희석한 후 **실온**에서 **1시간** 동안 반응시킨다. Secondary 항체와의 반응이 완료되면 PBST 혹은 TBST를 사용하여 washing을 **실온**에서 **10분간 3회** 반복한다.

**"Secondary 항체"** 는 primary 항체와는 다른 **goat나 donkey** 유래를 사용하는 것이 background를 줄일 수 있다.

Primary 항체를 **"monoclonal"** 로 사용할 경우 secondary 항체는 primary 항체의 **"subtype"** 에 적합한 것을 사용하여야 한다.

Detection을 위해 secondary 항체에 결합된 **"conjugate"** 는 **"Horseradish peroxidase (HRP)"** 와 **"Alkaline phosphatase (AP)"** 가 주로 사용된다.

**"AP"** 는 HRP보다 민감하지만 **"endogenous phosphatase"** 로 인해 **background**도 높아 HRP를 보다 많이 사용한다. AP를 conjugate로 사용하는 경우 skim milk는 blocking buffer로 적합하지 않다. Secondary 항체의 희석 비율은 제조사마다 **수백 배**에서 **수만 배**까지 다양하므로 제조사 매뉴얼에 따른다.

**"Detection의 마지막 단계"** 는, secondary 항체에 결합된 **"conjugate에 적합한 기질을 사용하여 표적 단백질을 검출"** 하는 과정이다.

HRP를 conjugate로 사용한 경우, **"chemiluminescence"** substrate인 **"Luminol"** 을 사용하여 film 혹은 digital imager를 사용하여 검출이 가능하다. **"DAB"** 와 같은 chromophoric substrate를 사용하면 불용성의 갈색 침전물을 형성하여 검출이 가능하다. 그 외 **"Fluorescent"** secondary 항체를 사용하여 형광으로 검출할 수 있다.

**"Chemiluminescence 검출 시약"** 은 감도에 따라 nano (10<sup>-9</sup>), pico (10<sup>-12</sup>), femto (10<sup>-15</sup>)로 나뉘며, 어떤 시약을 사용하느냐에 따라 표적 단백질 검출 유무가 결정될 정도로 중요하므로, 적합한 감도의 시약을 사용하여야 한다.

**"X-ray film"** 을 사용하는 경우에는 감광액 코팅이 **"단면"** 이냐 **"양면"** 이냐에 따라 검출 여부가 결정된다. Digital sensor를 장착한 imager를 사용할 경우, 검출 시간을 다양하게 조절하여 최적의 이미지를 얻을 수 있다.  
 

**WB에서 흔히 문제가 되는 몇 가지 이슈의 원인과 해결책**에 대해 알아보자.

**Table 8. Western blot troubleshooting**

![Western blot troubleshooting](https://www.ibric.org/upload/geditor/202010/0.37523800_1603194504.png)

**\[개념 요약\]**

-   **Western blot (WB)**: **"단백질"** 혼합물 시료에서 **"항체"** 를 probe로 사용하여 특정 **"단백질의 유무"**를 정량적으로 분석하는 방법

-   **WB 진행 4 단계:** 단백질 "**시료 조제"**, "**전기영동"** 으로 분자량에 따라 단백질 분리, gel에서 membrane으로 단백질 "**transfer"**, 항체를 사용하여 특정 단백질 "**검출"**

-   **WB 성공 요소**: 표적 단백질 최적 추출 조건, 전기영동 및 transfer 조건, 특이성 높은 항체 및 최적 사용 농도, 적절한 blocking 및 고감도 검출 방법

**참고문헌**

**SDS-PAGE** ([https://en.wikipedia.org/wiki/Western\_blot](https://en.wikipedia.org/wiki/Western_blot)), ([https://en.wikipedia.org/wiki/SDS-PAGE](https://en.wikipedia.org/wiki/SDS-PAGE))

**Sample preparation** ([https://www.abcam.com/protocols/sample-preparation-for-western-blot](https://www.abcam.com/protocols/sample-preparation-for-western-blot))

**Western blot** ([https://www.cusabio.com/m-244.html](https://www.cusabio.com/m-244.html))

**Western blot assembly** ([https://www.researchgate.net/figure/Western-Blot-assembly\_fig19\_5482465](https://www.researchgate.net/figure/Western-Blot-assembly_fig19_5482465))
