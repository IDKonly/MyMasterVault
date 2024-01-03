---
creation_date : 23.02.08
last_modified :
note_type : basic
category :
memo_level :
aliases : 
tags : []
---

Parent : [[_LabWorks]]

[[23.02.06 PCR condition check (2)]]에서 연결됨;

# [[Double cross-over homologous recombinant]] 

![[Pasted image 20230207162502.png]]

Double cross-over homologous recombinant란 host의 유전체에 삽입을 원하는 어떤 유전자를 삽입하는 기술이다.
편의상 유전자가 삽입되는 host DNA 혹은 삽입되기를 원하는 부위를 **target**, 우리가 삽입을 원하는 유전자를 **insert**라고 하면,
target 양쪽에 있는 일정길이의 DNA(40에서 50mer 정도의 길이)를 양 말단에 포함한 insert를 제작하여 host 안에 삽입하면, homology를 가진 유전자 서열끼리 교차(cross over)를 일으켜 target을 제거하고 insert가 삽입되는 현상을 이용한다.

# PCR-based TAP tagging strategy 

![[Pasted image 20230208112316.png]]

기본적인 전략은, homology를 insert에 부여할 primer를 디자인한다. 이때 primer의 구성은 약 20mer 정도의 insert를 포함한 amplicon을 만들어낼 universal primer와 유전자 삽입을 목적으로 하는 homology site를 합치는 방식으로 디자인하면 된다.

이렇게 만들어진 amplicon은 A’-insert-B’ 과 같은 형태로 증폭되는데, 이때 타겟에 존재하는 A-x-B sequence에 삽입된다. 결과적으로 삽입당하는 위치가 유전자의 stop codon이 존재하는 부분이라면 해당 유전자에서 나오는 단백질과 insert의 product가 fusion protein으로 생산된다.

insert가 tagging protein이면 tagging된 단백질을 얻을 수 있다.

# Primer design

![[Pasted image 20230208131314.png]]

[[The Tandem Affinity Purification (TAP) Method_ A General Procedure of Protein Complex Purification|Puig et al., 2001]]에서 plasmid DNA에 직접 결합하는 primer 길이를 20mer로 맞추기 위해 3mer를 더 늘린 버전(띄어쓰기 이후)을 이용한다
```
Forword primer – GTTACCGCAGACGAAACAGTAGATTTTTACGTGTACGATGA ATCCATGGAAAAGAGAAGATG (Tm=53˚C, SnapGene)
Reverse primer – TATATATTATATCCTCTAGTATATCAATGCAGTAGCAGCAG TACGACTCACTATAGGGCGA
(Tm=54˚C, SnapGene)
```
1.6k 길이의 amplicon을 얻을 수 있다.


![[Pasted image 20230208131213.png]]

```
Forword primer – GTTACCGCAGACGAAACAGTAGATTTTTACGTGTACGATGAAT CCATGGAAAAGAGAAGATG
Reverse primer – TATATATTATATCCTCTAGTATATCAATGCAGTAGCAGCAGT ACGACTCACTATAGGGCGA
```


띄어쓰기로 표시한 부분의 앞에있는 sequence가 Swd2의 유전자 말단을 뭉개고 들어가도록 homologous recombination을 일으키면서 뒤에 있는 TAP-tag까지 translation되게 한다.

![[Pasted image 20240103204157.png]]