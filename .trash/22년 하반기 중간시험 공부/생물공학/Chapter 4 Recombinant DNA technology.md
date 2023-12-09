-----
# Recombinant DNA technology

-   유전자 재조합 기술

## 기본개념

1.  Vector에 우리가 원하는 target DNA를 삽입하고 우리가 원하는 cloning 또는 expression을 얻는 것.
2.  source DNA와 target DNA 모두에 restriction enzyme을 처리하고, 이 둘을 ligase를 이용해 합성한다. 이 recombinant vector를 원하는 host cell에 삽입하고, 해당 target DNA에 encoding된 단백질을 발현시킨다.

## Restriction enzyme (제한효소)

1.  제한효소를 DNA에 처리하면 두가지 타입의 hand가 생긴다.
    1.  sticky hand - 두가닥의 DNA가 서로 다른 길이로 잘려 수소결합부위가 노출되어 있기 때문에, 결합 특이성과 반응성이 모두 좋다.
    2.  blunt hand - 두가닥의 DNA가 모두 같은 길이로 잘려 수소결합부위가 노출되어 있지 않기 때문에, 결합 특이성과 반응성이 모두 낮다.
2.  Restriction site mapping
    1.  같은 서로 다른 restriction enzyme 처리를 하면 각각의 절단부위에 따라 다른 길이의 DNA 조각들이 나오게 되는데, 이를 electrophoresis를 하면 이 서로 다른 길이의 DNA 조각을 식별할 수 있고, 따라서 전체 유전자에서 해당 restriction enzyme이 반응하는 위치를 추측하여 알 수 있다.

## Process

1.  target DNA의 원하는 단백질 유전자를 훼손시키지 않는 restriction enzyme을 처리해서, vector에 알맞는 sticky hand를 만든다.
    1.  이때 restriction enzyme을 하나만 처리하면, vector가 완성되었을때 해당 유전자가 발현되지 않을 가능성이 있다.
        1.  그 이유는 이미 잘린 유전자가 스스로 결합할 수 있기 때문인데, 두개를 처리하면 자가결합이 불가능해지므로 올바르게 결합될 확률이 높아진다.
        2.  그리고 단백질이 코딩된 위치가 반대로 결합해 오페론이 induction 할때 정상적으로 작동됨에도 불구하고 우리가 원하는 단백질이 발현되지 않을 수 있다.
2.  vector의 multiple cloning site(poly linker)에 맞는 restriction enzyme을 처리해 절단한다.
3.  두 DNA를 in vitro에 같이 넣으면, 각 DNA의 sticky hand가 반응하여 약하게 결합된다.
    1.  이때 두 DNA 간의 Nick이 생긴다.
    2.  이 과정을 anneling이라고 한다.
4.  ligase를 처리해서 위 과정에서 생긴 nick을 결합시킨다.
    1.  이때 주로 사용되는 ligase는 T4 phage로부터 추출한 T4 ligase를 사용한다.

# Vector

## Plasmid

1.  일반적 특성
    1.  host cell의 염색체와 독립적으로 분열하는 genetic element
    2.  small **circular or linear** DNA molecules
    3.  Range in size from **1kbp to up to 1Mbp**; typically **less then 5% of the size of chromosome**
    4.  Carry a variety of **nonessential**, but often very helpful, **genes**
    5.  Abundance(copy number) is variable
        1.  It is actually **controlled by origin of itself**
    6.  Each plasmid has **origin**
        1.  there is many **incompatibility(INC) groups**
        2.  Plasmids belonging to same Inc group exclude each other from replicating in the same cell but and coexist with plasmids from other groups
            1.  플라스미드는 같은 INC 그룹에 있는 오리진을 포함한 것들 끼리는 배타적인 관계를 가지고 있어 둘중에 하나를 없애려는 성질을 가지고 있음.
            2.  반면에, 다른 그룹에 있다면 같이 존재할 수 있음.
    7.  Some times they are cured by host
        1.  종종 분열된 host cell로부터 플라스미드가 없어지는 curing현상이 나타나는데, 이때 선택압력에 의해서 플라스미드가 없는 개체가 성장에 유리할 경우 plasmid를 가진 세포들의 비중이 낮아지는 현상이 생긴다.
2.  R plasmids
    1.  Resistance plasmids; confer resistance to antibiotics and other growth inhibiters
    2.  널리 퍼지고 잘 연구된 plasmid 그룹
    3.  Many are conjugative
        1.  많은 경우에 세포간 전달이 가능하다.
        2.  Tra regionn : Genes for conjugal transfer
3.  Cloning vector
    1.  pBR332
        1.  한개의 origin 과 두개의 selectable gene
        2.  Selection 방법이 replica plating을 요구하므로, selection이 번거롭고 귀찮음.
    2.  pUC19
        1.  한개의 origin과 한개의 amp 저항성 유전자, lac operon을 포함
        2.  Lac operon은 lacZ’가 코딩되어 있고, 해당 위치에 multipel cloning site가 포함되어 있음. * lacZ의 기능은 유지되어 있음
        3.  배지에 ampicillin과 X-gel을 포함시키고 세포들을 배양할 때, lacZ가 기능하면 X-gel을 분해하여 파란색을 띄므로, 흰색 콜로니를 형성한 세포가 우리가 원하는 세포가 됨
        4.  pBR332와 다르게 한번만 배양해도 되므로 편리함 (one step process)
4.  Expression vector
    1.  최대한 많은 양의 protein을 생산해내기 위한 강력한 promoter를 포함한다.
        1.  후술하겠지만, 다음 챕터에서 이 강력한 promoter를 어떻게 만드는지에 대한 내용이 있음
    2.  Polylinker라는 부위가 존재하는데, 이 부분에 적절한 제한효소 처리를 하고, cloning vector에 있는 DNA를 이식하면 쉽게 합성할수 있음.
    3.  CMV promoter와 같이 continuous promoter가 있는 경우도 있다.
        1.  근데 이후에 다루는 것 보면 대량배양할 때는 이런 프로모터가 들어가 있으면 세포가 성장하는데에 영향을 미치기 때문에 강력하게 조절되는 다른 프로모터를 더 많이 쓴다.
5.  Suttle vecter
    1.  두가지 이상의 host cell에서 사용하기 위해 오리진이 두개 이상 있는 vector이다.
    2.  왜 이딴걸 쓰냐면, 발현은 동물세포에서 하고 싶은데 클로닝을 동물세포에서 하면 돈이 많이 들잖아.. 그래서 클로닝은 E.coli에서 하고 발현은 동물세포에서 하고… ㅇㅋ?
6.  Alkaline phosphatase treatment
    1.  Self ligation을 막기 위해서 쓴다.
    2.  이 과정을 거치면 3’ end가 phosphate가 아닌 OH group이 되는데, ligase가 이 부위를 인식하지 못해 nick이 해소되지 않는다.
    3.  대신 처리된 DNA는 스스로와 반응하지 않으므로 결합 성공률이 올라간다.
    4.  이때 발생된 nick은 나중에 세포내에서 replication하면서 없어진다.
7.  Partial digestion
    1.  우리가 원하는 유전자를 얻을 확률을 높히기 위해서 사용된다.
    2.  보통 whole gene에 제한효소를 처리해서 적당한 크기로 자른 뒤에 클로닝 벡터에 삽입하는데, 이때 어지간하면 제한효소 때문에 DNA가 잘려버린다.
    3.  그래서 제한효소를 불완전하게 처리해서, 모든 부위가 잘리는 것이 아니라 부분적으로만 잘리게 한다.
    4.  그럼 상대적으로 긴 가닥이 생겨나게 되고, 평균적인 DNA조각의 길이가 늘어나게 되므로
    5.  아래 공식에 의해서 우리가 원하는 유전자가 발견될 확률이 올라간다.$$ N=ln(1-P)/ln(1-f) $$
        1.  N = 콜로니의 갯수
        2.  P = 우리가 원하는 유전자를 찾을 확률
        3.  f = insert의 평균 크기/전체 유전자의 크기

### Virus vector

1.  더 큰 용량(15kb)
2.  진화된 생물의 매커니즘을 이용해서 그런가.. 감염될 확률이 아주 높아서 transformation 비율이 매우 높다.
3.  조작한 유전자와 바이러스 단백질을 시험관에 넣으면 합성된다.
    1.  이때 유전자에 필수적으로 들어가야 하는 sequence들이 있다.
    2.  특히 cos site.
    3.  넣고자 하는 조작된 DNA의 길이가 특정 길이여야 한다. 길거나 짧으면 합성되지 않는다. (50kb)
4.  Lysogenic cycle에 필요한 유전자를 싹다 쳐냈기 때문에 무조건 lytic cycle만 한다 = 감염되면 필연적으로 용균반(plaque)이 생성된다.

### Cosmid

1.  더더 큰 용량(45kb)
2.  근본적으로 플랫폼은 virus를 공유한다. 근데 이제 바이러스로의 DNA는 다 쳐내서 plaque를 만들지는 않는다.
3.  Plasmid와 동일한 구성이지만 cos site는 바이러스 파티클이랑 결합해야 하니까 있음
4.  Selectable marker 있어야함

### BAC (Bacterial Artificial chromosome)

1.  F plasmid 이용함
2.  1~2카피만 존재할수 있음
3.  존나큰용량(100kb)
4.  다른 세포에 전달하기도 함 (conjungation)
    1.  너무 커서 heat shock으로는 삽입할 수 없고, electroporartion 같은 방법으로 삽입해야함.

## Selection

1.  각 vector는 selectable marker를 가지고 있다.
2.  Antibiotic 저항성 유전자로 가지고 있는데,
3.  pBR322 의 경우 AMP와 TET저항성 유전자를 가지고 있다.
4.  DNA 가 TET위치에 삽입되었다면, 해당 저항성 유전자가 파괴된다.
5.  Amp 포함 배지에서 세포를 배양하면 해당 플라스미드를 포함하지 않은 세포는 사멸한다.
6.  해당 세포를 replica plating한 뒤에 tet를 포함한 배지에서 키우면, 이때 사멸한 위치의 세포가 우리가 원하는 DNA를 포함한 플라스미드를 가진 세포가 된다.
    1.  <u>하지만 이때 어떤 세포가 어떤 DNA를 포함하고 있는지 모르므로, library라고 부른다</u>

## Screening

1.  Selection에서 만든 DNA library에서 우리가 원하는 DNA를 찾기 위한 실험

### method
1.  DNA probe
    1.  만드는법
        1.  *Random primer method*
            1.  우리가 원하는 유전자에다가 6bp짜리 랜덤 프라이머를 뿌려서 짧은 DNA조각을 만들고 이걸 프라이머로 이용
        2.  *Chemical synthesis*
            1.  그냥 화학적 합성으로 프로브를 설계한다.
            2.  단백질의 구조를 알고 있으면 이걸 역설계해서 제작함
            3. [[근데 사실 염기서열을 알고 있으면 뭐하러 probe를 만들겠음 PCR 하면 되지]]
2.  Labeling(taging)
    1.  Radioactive
        1.  P32
        2.  S35
    2.  Non-radioactive
        1.  Digoxigenin
	        1. DIG-specific antibody
        2.  Horseradis peroxisidase system or alkaline phosphate
        3.  Biotin - streptavidin
            1.  바이오틴과 스트랩타비딘은 반응성이 좋다.
            2.  바이오틴은 DNA에 붙어있고, 스트랩타비딘은 alkaline phospate를 달고 있어서 적절한 기질을 투입하면 해당 위치에서 표시가 남
        4.  형광물질
        5.  X-phos 와 Lumi-phos
3.  Protein
    1.  Immunologycal screening
    2.  Protein activity screening
        1.  대상 유전자가 생산하는 단백질이 특정 기질을 시각적으로 판별할수 있도록 변형시킨다면, 해당 단백질이 기능하는 것을 관찰하여 해당 유전자를 포함하고 있는 세포주를 찾는다.
    3.  Functional complementation
        1.  미니멀 배지에서 생존에 필수적인 유전자를 탈락시킨 host cell을 준비한다.
        2.  해당 유전자를 포함한 vector를 받았다면 해당 세포는 미니멀 배지에서 생존한다
        3.  Profit!

## cDNA library

1.  Eukaryotic은 인트론과 엑손으로 이루어져 있어 그냥 DNA를 뽑아서 prokaryotic에 넣으면 단백질이 생산되지 않는다.
    1.  그러므로 인트론이 제거된 유전자를 추출해서 넣어야 하는데,
    2.  mRNA를 역돌격시키면 인트론이 제거된 DNA를 얻을수 있다.
2.  mRNA는 poly-A tail을 이용해서 oligo-dT가 박힌 비드를 이용해서 분리한다.
3.  해당 RNA를 역전사하는데,
    1.  되다만놈들도 있어서 문제가 된다….는데 이거 어떻게 처리한다고 했는지 기억안남… 단백질 액티비티로 검사하면 되는거 아닌가?
4.  여하튼 추출한 세포에서 발현되는 유전자만 뽑아낼수 있다.