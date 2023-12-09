------
# Expression vector

cloning 된 유전자를 host cell에서 발현시키는 것을 공부

상업적인 면에서 단백질을 고효율로 만들어 내는 것이 중요

이를 위해서 특별한 발현벡터를 쓰는데, transcription, translation, protein stabilty, secretion를 컨트롤할 수 있는 vector를 쓴다.

Gene expression vector는 promoter, terminator sequences, strecnth of the ribosome-binding site, the number of copies and the cloned gene is plasmid borne or intergrated into the genome of host cell, cell location of product, efficiency of translation, intrinsic stability of the cloned gene protein within host cell 를 구성요소로 포함한다.

1.  Bacterial expression vector
    1.  구성
        1.  promoter (P)
        2.  operator (O)
        3.  polylinker
        4.  transcription termination sequence
        5.  selectable genetic marker
        6.  origin
        7.  gene encoding repressor that bind O and regulates P
2.  Mammalian expression vector

# Commercial manufacture of a recombinant-DNA derived product

1.  Gene cloning: cloning vector
2.  Selection and into expression vector
3.  성장배양
4.  생산배양
5.  분리정제 (protein purification)
6.  패키징 (formulation and packaging)

# Promoter

## Gene Expression from strong and regulatable promoters

1.  Promoter의 최소 요구사항
    1.  유전자 발현 시스템의 최소요구조건은 강하고 조절가능한 프로모터(strong and regulatable promoter) 시퀀스를 클론인자의 upstream에 가지고 있어야 한다는 것이다.
    2.  ‘강한 promoter’란 RNA polymerase와의 affinity가 높다는 것이고
    3.  ‘조절능력이 있는 promoter’란 정확한 방식으로 transcription의 양을 조절할 수 있게 한다.
2.  이게 안되면, 즉, 우리가 세포의 유전자 전사능력을 조절할 수 없으면 세포는 잘 자랄 수 없다. (세포가 성장에 필요한 리소스를 계속해서 억제 당하게 되므로)
    1.  심지어 plasmid가 host cell로부터 curing될 수도 있음!!
3.  그래서 단백질을 잘 생산하기 위해서는 이걸 IPTG같은걸 써서, 세포가 다 자란 다음부터 단백질을 발현시키도록 하는 편이 좋다.

## Sigma factor

1.  개요
    1.  Sigma factors recognize two highly conserved regions of promoter
    2.  Two regions within promoters are highly conserved
        1.  Pribnow box : located 10 bases before the start of transcription(-10 region)
        2.  -35 region : located ~35bases upstream of transcription
    3.  이 두 부분이 대부분의 프로모터에서 거의 일치한다.
        1.  이 부분(prinbow box, -35 region)은 consensus region이라고 한다.
        2.  이 부분을 정확하게 인지해서 sigmafactor가 인지한다.
        3.  이 sigma factor가 없는 RNA polymerase를 coenzyme이라 한다
        4.  있는 애는 Holoenzyme이라고 한다.
    4.  Termination of RNA synthesis is governed by a specific DNA sequence
        1.  Intrinsic terminators : transcription is terminated without any additional factors
        2.  Rho-dependant termination : Pho protein recognizes sqecific DNA sequences and causes a pause in the RNA polymerase
2.  인조 프로모터
    1.  그래서 자연계에 존재하는 프로모터들을 봤더니, 많은 프로모터들이 위에서 발견한 완벽한 프로모터를 가지고 있지 않더라
    2.  그래서 이 부분을 우리가 유전자 조작을 통해서 완벽한 상태의 sequence로 바꿔줬더니 강해지더라~

# Controlling expression

1.  Catabolite repression in catabolism
    1.  포도당이랑 유당을 따로따로 쓴다.
    2.  선호도가 정해져 있다는 이야기
    3.  그럼 포도당을 쓰고 있을 때에는 유당을 쓰기위한 유전자는 활성화 되어있지 않다.
    4.  Greasing the wheels for transcription
        1.  Activater and effector
            1.  Effecter가 있으면 normal transcription, 없으면 increased transcription.
        2.  Overall regulation of the lactose operon
            1.  CAP : Catabolite Activater Protein 이 있다.
            2.  CAP는 cAMP에 의해서 조절 받음
    5.  LacUV5 promoter는 catabolite repression을 망가트려서 포도당이 배지내에 존재하더라도 IPTG induction을 하면 바로 발현시킬 수 있다.
2.  Temperture senesitive promoter - pL promoter with cI repressor
    1.  The pL promoter is controlled by the cI repressor protein of bacteriophage lamda
    2.  42도가 되면 cI 단백질이 망가져서 transcription이 된다.
3.  Gene d10 promotor from bacteriophage T7
    1.  T7은 E.coli의 프로모터를 이용하지 않고 자기 자신의 프로모터를 사용하는데, 거기다가 자기 자신의 자체적인 RNA polymerase를 쓴다.
    2.  pET vecter에 이 프로모터가 적용되어 있다.
    3.  진짜 존나 쌘 프로모터라서 expression에 좋다.
    4.  사용법
        1.  LacZ’ 같은 데에 T7 RNA polymerase의 유전자를 넣어서 해당 벡터에서 T7 polymerase를 생산하게 한다.
            1.  당연히 이때 LacI 도 있기 때문에 LacZ’는 조절 받고 있다.
        2.  그리고 T7 promotor 뒤에 target gene을 삽입해서 T7 poly가 만들어질 때 생산되게 된다.
        3.  그럼 IPTG induction 조건 하에 강력한 T7 promotor 의 발현을 맛 볼 수가 있다
4.  만약에 repressor가 너무 많거나 너무 적다면
    1.  많으면 transcription 조건이 갖춰 졌음에도 불구하고 발현되지 않을 것
    2.  적으면 조건이 갖춰지지 않았음에도 불구하고 발현되어 버릴 것.
    3.  그럼 prometer랑 represser의 유전자 비율을 각자 다른 플라스미드에 넣어서 인위적으로 조절해버리자
        1.  represser는 low copy number plasmid에 넣고
        2.  Repressor는 high copy number plasmid에 넣었더니
        3.  대충 원하는 대로 되더라
        4.  근데 이러면 origin을 여러 개 써야 된다… 아니면 incompatiblity 때문에 서로 충돌이 일어나서 잘 안된다..
    4.  어떤 plasmid의 copy number를 늘리고 싶으면 rop 유전자를 박살내면 된다… 얘가 증폭량을 엄청 잘 조절하고 있기 때문에… 박살내면 조절이 안돼서 존나 200개씩 만든다

## Increasing protein production

-   ?

# in Large-scale systems

1.  Temp-sensitive 도 전체 용량이 커지면 온도를 높이는 데에 너무 높은 비용이 든다
2.  IPTG도 좀 비싸다
3.  그래서 저렴하게 large-scale system에서 expression을 유도하는 방법으로 배지성분변화를 이용한다.
    1.  Trptophan ← 저렴함
    2.  p^trp으로 cI repressor를 조절.

## Expression in other microorganism

1.  E.coli에서 잘 되는게 다른데에서도 잘 됐으면 좋겠지만 그렇지는 않다..
2.  Nm promoter가 강력하드라
    1.  Neomicin resistence gene에서 추출한 프로모터
3.  pAV10 : Universal gram-negative expression vector
    1.  Low-copy broad-host-range universal expression vector
    2.  Tn5 promoter사용
4.  Constitutive promoters
    1.  이거 그냥 확률적으로 때려박아서 가장 강력한 프로모터를 만들었단 얘기잖아
    2.  Promoter를 인공합성했음

# Fusion protein

가끔, 외래단백질들, 특별히 작은 애들은, host cell이 자기한테 필요 없는 단백질이라고 생각해서 degradation 할 때가 있다.

이걸 해결하는 방법이 뭐냐?

host cell이 분해하지 않는 단백질을 같이 합쳐서 생산하면 이 fusion protein을 자기한테 필요한 단백질이라고 생각해서 해당 단백질을 파괴시키지 않는다.

이렇게 하지 않아서 proteolysis가 일어난다면 아무리 강력한 프로모터를 써서 아무리 많이 단백질을 생산해 내더라도 아무런 의미가 없다.

E.coli랑 B.subtilis가 진짜 proteolysis를 잘 일으킨다

그래서 이 둘을 합치는데, 두 단백질의 reading frame이 어긋나면 만들고 싶은 단백질이 제대로 합성되지 않으므로 조심해야한다.

## Molecular basis of mutation

1.  Silent mutation
    1.  Does not affect amino acid sequence
2.  Missense mutation
    1.  Amino acid changed; polypeptide altered
3.  Nonsense mutation
    1.  Codon becomes stop codon; polypeptide is incomplete
4.  Deletions and insertions cause more dramatic changes in DNA
5.  Frameshift mutation (중요)
    1.  Deletions or insertions that result in a shift in the reading frame
    2.  Often result in complete loss of gene funtion
    3.  이렇게 되지 않게 correct reading frame에 맞게 fusion시킨다.

## Cleavage of fusion proteins

1.  Fusion protein을 만들 때, 우리가 원하는 단백질을 정상적으로 동작하게 하려면 잘라서 우리가 원하는 단백질만 남겨야 한다.
    1.  그러면 stable한 단백질과 target 단백질 사이에 site of cleaveage를 삽입해서 이 부위에 맞는 protease를 처리한다.

## Use of fusion proteins

1.  Fusion protein cloning vector
    1.  ompF와 lacZ’ 사이에 insert site가 있다.
        1.  ompF = E.coli outer membrane pretein
    2.  LacZ’는 reading frame이 망가진 상태라서 기능을 하지 않음
    3.  타겟 유전자를 집어넣으면 reading frame이 복구되므로 lacZ가 활성화된다.
    4.  그럼 이 세개의 단백질이 합쳐져서 만들어지므로 ‘tribrid’ protein이 만들어진다

### fusion systems used to facilitate the purification of foreign

1.  Fusion protein을 쓰면 분리정제가 쉬워진다.
2.  Affinity cromatograpy and immunochromatograpy
    1.  어쨋거나 둘 다 꽁무니 잡는 애들
    2.  각종 태그를 이용해서 분리정제를 할 수 있는데,
3.  tags(fusion partner)
    1.  His tail
        1.  <u>Ni2+ Or Co2+/ ligand</u>
        2.  Imidazole / Elution condition
        3.  배위결합
            1.  비 공유 전자쌍을 공유함으로 이루어진 결합
            2.  이 경우, 니켈(또는 코발트)과 histon 단백질의 질소부위가 배위결합으로 반응해서 붙잡는다.
    2.  8Flag
        1.  Specific MAb(monoclonal antibody) / ligand
        2.  Low calcium / Elution condition

### Immunoaffinity chromatographic purification of a fusion protein

1.  To simplify the furification of recombinant proteins
2.  The marker protein to be removed by bovine intestinal enterokinase
    1.  Enterokinase : 특정 아미노산 서열을 인식해서 해당 부분을 자른다.

## Chromatograpy

1.  LPLC
	1. low pressure liquid chromatography
2.  HPLC
	1. High pressure liquid chromatography
3.  FPLC
	1. Fast protein liquid chromatograph

# Surface display

## Viral surface display for screening

### M13 bacteriophage system

1.  ssDNA(+) genome

### how displaying use M13 phage

1.  M13 phage는 cell lysis를 일으키지 않고 세포 밖으로 나오는 life cycle을 가지고 있음.
2.  이 바이러스의 유전자중 pIII protein이 있는 부위에 target 유전자를 fusion protein으로서 삽입하면
3.  머리부분에 해당 단백질이 붙은 M13이 생산됨. (Surface display)
4.  이 M13을 immobilized 하면 해당 항체에 결합되는 M13만 남음

## Bacterial surface display

1.  박테리아도 똑같이 outer membrane protein에 fusion protein으로서 타겟을 넣어주면 surface display할수 있음
2.  이때 특정한 antigen을 fusion protein으로 넣어주면 백신으로 이용할 수 있다.


# Mammalian expression vector
1. 사이토 메갈로 바이러스 프로모터
2. MCS
3. poly(A) templete
4. f1 ori
5. 네오마이신 셀렉터블 마커
6. SV40 pA
7. pUC ori
8. Ampicillin


# DNA integration into the host chromosome
1. 플라스미드를 쓸 경우 카피넘버가 많아 대량의 DNA를 얻기에는 좋지만, 반면에 Plasmid curing이 일어날 가능성이 있다.
2. Target DNA가 host의 DNA 안에 들어간다면 이런 현상이 일어나지 않으므로, DNA를 유전자에 넣으면 안정적으로 단백질을 생산할 수 있다.
	1. =stability가 높다
3. T7 expression system(pET vector)
	> For integration of DNA into a chromosomald site, the input DNA must share som sequebce similarity....

	1. <u>Identify the desired chromosomal integration site</u>, i.e., a segment of DNA on the host chromosome that can be discupted **without affecting the normal functions of the cell**
	2. <u>Isolate and clone part of all or the chromosomal integration site</u>
	3. Ligate and clone gene and a regulatable promoter either into or adjacent to the cloned chromosomal integration site.
	4. <u>Transfer the chromosomal integration fragment-cloned gene</u> construct into the host cell as **part of a plasmid that cannot replicate in the host cell.**
	5. <u>select and perpetuate host cells that express the cloned gene.</u> propagation of the cloned gene can occur **only if it has been integrated** into the chromosomal DNA of the host cell.

## Cross over DNA
1. cross over
	1. target region에 essential gene이 있으면 안된다.
	2. 확률이 낮다.
	3. 이것에 쓰이는 plasmid가 chromosome과 별개로 분열하면 안된다.
		1. 즉, origin이 없다
	4. 삽입되어야 하는 유전자에 seletable marker도 들어가 있다.
2. Double cross-over
	1. integration fragment가 두개인 plasmid이다.
	2. 두개의 fragment 사이의 유전자가 들어간다. 즉, plasmind의 일부(middle of a cloned segment of DNA)만 삽입된다.
	3. **results in integration of the cloned gene**
3. single cross-over
	1. integeration fragment가 하나인 plasmid이다.
	2. 플라스미드 전부가 삽입된다.
	3. **results in the integration of the entire plasmid**
4. 문제점
	1. **숙주의 염색체 안에서 한개 카피만 존재하기 때문에, 단백질 생산량이 낮다.**
5. 문제점의 해결
	1. **점진적으로 고농도의 항생제에서 세포를 배양하면, 세포는 이에대한 저항성을 더 얻기 위해 유전자를 여러 카피로 늘리므로, 그에 인접한 유전자도 함께 늘어날 것이다.**