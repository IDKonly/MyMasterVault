-----
# Recombinant DNA technology

-   유전자 재조합 기술

## 기본개념

1.  Vector에 우리가 원하는 target DNA를 삽입하고 우리가 원하는 cloning 또는 expression을 얻는 것.
2.  source DNA와 target DNA 모두에 restriction enzyme을 처리하고, 이 둘을 ligase를 이용해 합성한다. 이 recombinant vector를 원하는 host cell에 삽입하고, 해당 target DNA에 encoding된 단백질을 발현시킨다.



## Process


2.  vector의 multiple cloning site(poly linker)에 맞는 restriction enzyme을 처리해 절단한다.
3.  두 DNA를 in vitro에 같이 넣으면, 각 DNA의 sticky hand가 반응하여 약하게 결합된다.
    1.  이때 두 DNA 간의 Nick이 생긴다.
    2.  이 과정을 anneling이라고 한다.
4.  ligase를 처리해서 위 과정에서 생긴 nick을 결합시킨다.

# Vector

## Plasmid

1.  일반적 특성
    1.  host cell의 염색체와 독립적으로 분열하는 genetic element
 
   
    4.  Carry a variety of **nonessential**, but often very helpful, **genes**
    5.  Abundance(copy number) is variable
        1.  It is actually **controlled by origin of itself**
    6.  Each plasmid has **origin**
        1.  there is many **incompatibility(INC) groups**
        2.  Plasmids belonging to same Inc group exclude each other from replicating in the same cell but and coexist with plasmids from other groups
            1.  플라스미드는 같은 INC 그룹에 있는 오리진을 포함한 것들 끼리는 배타적인 관계를 가지고 있어 둘중에 하나를 없애려는 성질을 가지고 있음.
            2.  반면에, 다른 그룹에 있다면 같이 존재할 수 있음.
  
        
        $$ N=ln(1-P)/ln(1-f) $$
        
        1.  N = 콜로니의 갯수
        2.  P = 우리가 원하는 유전자를 찾을 확률
        3.  f = insert의 평균 크기/전체 유전자의 크기

### Virus vector

1.  더 큰 용량(15kb)
2.  진화된 생물의 매커니즘을 이용해서 그런가.. 감염될 확률이 아주 높아서 transformation 비율이 매우 높다.
3.  조작한 유전자와 바이러스 단백질을 시험관에 넣으면 합성된다.
    1.  이때 유전자에 필수적으로 들어가야 하는 seq들이 있다.
    2.  특히 cos site.
    3.  넣고자 하는 조작된 DNA의 길이가 특정 길이여야 한다. 길거나 짧으면 합성되지 않는다. (50kb)
4.  Lysogenic cycle에 필요한 유전자를 싹다 쳐냈기 때문에 무조건 lytic cycle만 한다 = 감염되면 필연적으로 용균반(plaque)이 생성된다.



## Selection

1.  각 vector는 selectable marker를 가지고 있다.
2.  Antibiotic 저항성 유전자로 가지고 있는데,
3.  **pBR322 의 경우 AMP와 TET저항성 유전자를 가지고 있다.**
4.  DNA 가 TET위치에 삽입되었다면, 해당 저항성 유전자가 파괴된다.
5.  **Amp 포함 배지에서 세포를 배양하면 해당 플라스미드를 포함하지 않은 세포는 사멸한다.**
6.  **해당 세포를 replica plating한 뒤에 tet를 포함한 배지에서 키우면, 이때 사멸한 위치의 세포가 우리가 원하는 DNA를 포함한 플라스미드를 가진 세포가 된다.**
    1.  **하지만 이때 어떤 세포가 어떤 DNA를 포함하고 있는지 모르므로, library라고 부른다**

## Screening

1.  **Selection에서 만든 DNA library에서 우리가 원하는 DNA를 찾기 위한 실험**

### method

1.  DNA probe
    1.  만드는법
        1.  **Random primer method**
            1.  우리가 원하는 유전자에다가 6bp짜리 모든 프라이머를 뿌려서 짧은 DNA조각을 만들고 이걸 프라이머로 이용
        2.  Chemical synthesis
            1.  그냥 화학적 합성으로 프로브를 설계한다.
            2.  **단백질의 구조를 알고 있으면 이걸 역설계해서 제작함**
	            1. **minimun codon degenerancy를 이용함**
2.  Labeling(taging)
    1.  Radioactive
        1.  P32
        2.  S35
    2.  Non-radioactive
        1.  **Digoxigenin**
	        1. **특이적인 Antibody를 이용해 검출한다.
		        1. **이 항체는 형광물질이나 Alkaline phospatase를 가지고 있어서 검출해낼수 있다.**
        2.  Horseradis peroxisidase system or alkaline phosphate
        3.  **Biotin - streptavidin**
            1.  **바이오틴과 스트랩타비딘은 반응성이 좋다.**
            2.  **바이오틴은 DNA에 붙어있고, 스트랩타비딘은 alkaline phospate를 달고 있어서 적절한 기질을 투입하면 해당 위치에서 표시가 남**
        4.  형광물질
        5.  X-phos 와 Lumi-phos

## cDNA library

1.  **Eukaryotic은 인트론과 엑손으로 이루어져 있어 그냥 DNA를 뽑아서 prokaryotic에 넣으면 단백질이 생산되지 않는다.**
    1.  그러므로 인트론이 제거된 유전자를 추출해서 넣어야 하는데,
    2.  **mRNA를 역전사시키면 인트론이 제거된 DNA를 얻을수 있다.**
2.  **mRNA는 poly-A tail을 이용해서 oligo-dT가 박힌 비드를 이용해서 분리한다.**
	1. **비드를 통과한 액체에는 mRNA를 제외한 모든 RNA가 나오고,**
	2. **Elution buffer로 비드에 붙어있는 RNA를 제거하면 mRNA를 얻어낼 수 있다.**
3.  해당 RNA를 역전사하는데,
    1.  되다만놈들도 있어서 문제가 된다….는데 이거 어떻게 처리한다고 했는지 기억안남… 단백질 액티비티로 검사하면 되는거 아닌가?
    2. 이때 나온 cDNA는 모든 mRNA의 cDNA이다. 즉, library이다.
    3. 이때 이용해주는 primer도 oligo dT
    4. 다양한 종류의 cDNA의 얻게 된다.
4.  여하튼 추출한 세포에서 발현되는 유전자만 뽑아낼수 있다.