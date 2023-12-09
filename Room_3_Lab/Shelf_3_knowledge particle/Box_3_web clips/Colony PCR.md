---
title:
  - 실전 실험 프로토콜 101
creation_date: 3
note_type: Webclips
category: 
memo_level: 
aliases: 
tags:
  - BRIC
  - 실전_실험_프로토콜_101
  - PCR
  - Colony
---

Parent : [[_Webclips]]

[[ReadItLater]] [[Article]]

# [실전 실험 프로토콜 101 #3. 누구보다 빠르게…](https://www.ibric.org/myboard/read.php?Board=news&id=332851&BackLink=L215Ym9hcmQvbGlzdC5waHA/Qm9hcmQ9bmV3cyZQQVJBMz0xMTA=)

**프라이머 (primer) 디자인**

두 번째 이야기에서 Multi-Exon-Skipping Detection Assay (MESDA)로 타깃 유전자의 새로운 아이소폼 (isoform)인 엑손 (Exon) 6B를 찾은 이야기와 몇 개월 후 다른 연구팀에서 이를 뒷받침하는 논문이 나왔다는 내용을 소개하였습니다 \[출처 1\]. 새롭게 찾은 엑손 6B를 포함하는 아이소폼의 추가적인 연구를 위해 엑손 6B를 포함하는 cDNA의  cording region을 PCR로 증폭하기 위한 프라이머를 디자인했습니다. 프라이머 디자인을 위해 프로그램을 이용하기도 하지만, 개인적으로는 주어진 시퀀스 (sequences)를 바탕으로 직접 프라이머를 디자인합니다 \[출처 2\]. cDNA를 이용한 PCR를 할 때는 proofreading이 되는 polymerase를 사용하면 됩니다 \[출처 3\]. 프라이머를 디자인할 때 N-terminal 쪽에 3개 카피의 FLAG (3X-FLAG)를 넣어서 endogenous 타깃 단백질과 구별을 할 수 있습니다. 여기서 또 하나 주의할 점은 3X-FLAG에 이미 start codon (ATG)를 포함했기 때문에 타깃 유전자의 cording region에서 ATG 시퀀시를 없애고 프라이머를 디자인해야 합니다. 

**라이게이션 (Ligation)과 콜로니 (Colony) PCR**

디자인한 프라이머로 PCR를 한 후 6% native polyacrylamide 젤 (PCR 밴드의 크기의 따라 결정)에 로딩을 하고, 타깃 밴드를 칼로 조심스럽게 잘라냅니다. 잘라낸 부분을 \[crush and soak\] 방법으로 DNA를 뽑은 다음, 엔자임을 처리하고 mammalian expression vectors (같은 혹은 상용되는 엔자임으로 처리)에 집어넣었습니다 (라이게이션). 벡터와 인서트 (엑손 6B를 포함한 아이소폼)를 라이게이션을 할 때, QUICK Ligation을 하면 짧은 시간 (5분)에 라이게이션을 할 수 있습니다 \[출처 4\]. 라이게이션을 할때 벡터와 인서트 비율은 NEBcalcultor에 가서 원하는 비율로 라이게이션을 하면 됩니다 \[출처 5\].

라이게이션이 끝나면 형질전환 (transformation)을 해서 37도에서 오버나잇으로 키웁니다. 이때 벡터가 가지고 있는 항생제를 처리한 플레이트에서 키웁니다. 다음 날 플레이트에 자란 콜로니를 10 µl의 RNase, DNase free 물에 푼 다음 그중에 2 µl를 이용해서 콜로니 PCR을 합니다. 콜로니 PCR를 한 후 타깃 밴드가 나온 것만 항생제를 포함한 4 ml LB에 키워서 미니프렙 (miniprep)을 합니다. 미니프렙을 한 후 추가로 엔자임 커트를 해서 인서트가 들어있는지 없는지 확인을 합니다. 두 개의 다른 엔자임을 사용할 때 NEB double digest 사이트에서 두 엔자임을 함께 사용할 수 있는 버퍼 (buffer)를 확인할 수 있습니다.

![콜로니](Room_0_metadata/Shelf_0_Resource/콜로니.png)

**그림1. 콜로니 PCR  
출처: [https://www.youtube.com/watch?v=1Wth5zGOEEM](https://www.youtube.com/watch?v=1Wth5zGOEEM)**

  
**시퀀싱 (Sequencing)**

엔자임 컷으로 인서트가 들어간 것을 확인한 후 마지막으로 시퀀싱을 보냅니다. 시퀀싱을 보낼 때 시퀀싱 프라이머는 인서트가 들어가 있는 지역보다 위쪽으로 100 bp 정도 떨어진 지역의 시퀀싱 프라이머를  사용합니다. 시퀀스만 빠르게 확인하는 방법으로 인서트를 T-Vector에 넣는 방법이 있는데, 이때 주의할 점은 proofreading이 되는 polymerase 중 polymerase 종류에 따라서 A를 추가적인 방법 (A-Tailing)으로 붙여서 클로닝 (cloning)을 해야 하는 경우도 있습니다 \[출처 6\]. 시퀀싱 결과가 나오면 blastn \[출처 7\] 혹은 SnapGene \[출처 8\]과 같은 프로그램을 이용해서 cDNA가 제대로 들어갔는지 확인을 합니다.

![SnapGene Viewer로 본 시퀀싱 결과](Room_0_metadata/Shelf_0_Resource/SnapGene%20Viewer로%20본%20시퀀싱%20결과.png)

**그림2. SnapGene Viewer로 본 시퀀싱 결과  
\[출처: 본인\]**

  
**하루 만에 플라스미드 증폭하기** 

실험을 하다 보면 준비해 놓은 플라스미드가 예상보다 빨리 없어지는 경우가 있습니다. 이럴 때 글리세롤 (glycerol) 스탁 (stock)을 만들어 놓으면 LB에 키워서 다음날 플라스미드를 뽑아서 사용할 수 있습니다. 하지만, 글리세롤 스탁이 오래되어서 다음날 자라지 않는 경우가 있고, 글리세롤 스탁이 없는 경우는 플라스미드를 형질전환한 다음 플레이트에 키웁니다 (1일). 다음날 플레이트에서 콜로니를 LB에 키워서 플라스미드를 뽑아서 사용해야 합니다 (1일). 이럴 경우 플라스미드를 얻는 데까지 2일이 걸립니다. 하루의 시간을 단축하기 위해서 형질전환 것을 플레이트에서 키우지 않고, 형질전환 한 다음 바로 항생제가 들어 있는 LB에 키워서 다음 날 미니프렙을 통해 플라스미드를 얻을 수 있습니다. 플레이트에서 키우는 과정을 생략함으로써 하루를 단축할 수 있습니다. 

타깃 유전자의 인트론 (intron) 6 지역의 Alu 시퀀스로 인해 만들어진 새로운 엑손을 찾았고, 그 아이소폼이 단백질을 발현하는 것을 확인하기 위해 mammalian expression vectors에 어떻게 인서트 (cording region)를 집어넣는지를 알아보았습니다. Alu 시퀀스에 대해 알아보다가 서로 다른 방향의 Alu 시퀀스가 같은 인트론 혹은 인근 인트론에 있으면 이 Alu 시퀀스들이 결합하여 스플라이스 사이트 (splice site)들을 서로 가까이하여 스플라이싱 (splicing)이 일어나서 circular RNA를 만든다는 것이 보고되었습니다. 이러한 이유로 Alu 시퀀스를 많이 포함하고 있는 타깃 유전자가 circular RNA를 만든다고 가정하였습니다. Alu 시퀀스를 많이 포함한 타깃 유전자에서 어떻게 circular RNA가 만들어지는지 다음 이야기에서 좀 더 자세히 알아보겠습니다. 

**출처**

1.  [https://www.ibric.org/myboard/read.php?Board=news&id=331751&Page=1](https://www.ibric.org/myboard/read.php?Board=news&id=331751&Page=1)
2.  [https://www.idtdna.com/pages/education/decoded/article/designing-pcr-primers-and-probes](https://www.idtdna.com/pages/education/decoded/article/designing-pcr-primers-and-probes)
3.  [https://www.neb.com/tools-and-resources/selection-charts/dna-polymerase-selection-chart](https://www.neb.com/tools-and-resources/selection-charts/dna-polymerase-selection-chart)
4.  [https://international.neb.com/protocols/0001/01/01/quick-ligation-protocol](https://international.neb.com/protocols/0001/01/01/quick-ligation-protocol)
5.  [https://nebiocalculator.neb.com/](https://nebiocalculator.neb.com/)
6.  [https://international.neb.com/protocols/2013/11/01/a-tailing-with-taq-polymerase](https://international.neb.com/protocols/2013/11/01/a-tailing-with-taq-polymerase)
7.  [https://blast.ncbi.nlm.nih.gov/Blast.cgi?PAGE=MegaBlast&PROGRAM=blastn&BLAST\_PROGRAMS=megaBlast&PAGE\_TYPE=BlastSearch&BLAST\_SPEC=blast2seq&DATABASE=n/a&QUERY=&SUBJECTS=](https://blast.ncbi.nlm.nih.gov/Blast.cgi?PAGE=MegaBlast&PROGRAM=blastn&BLAST_PROGRAMS=megaBlast&PAGE_TYPE=BlastSearch&BLAST_SPEC=blast2seq&DATABASE=n/a&QUERY=&SUBJECTS=)
8.  [https://www.snapgene.com/](https://www.snapgene.com/)