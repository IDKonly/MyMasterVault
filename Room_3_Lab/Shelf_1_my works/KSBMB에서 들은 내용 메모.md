---
creation_date : 23.05.12
last_modified :
note_type : basic
category :
memo_level :
aliases : 
tags : []
---

Parent : [[]]

# day 1

1. Single cell / multi modal
2. stmulation 3D genome
	1. Nature method - “Hi-C”
	2. Promoter DNA methylation → gene repressed
3. Hi-C 
	1. Seq 데이터에서는 멀어보이지만 물리적으로 가까운 두 유전자 가닥을 알아낼 수 있음.
4. **TAD → Topologicaly associated domain**
5. Hi-C break point
6. “Enhancer hijacking”
7. 3D genome 
	1. Pre-Trained model = AI 말하는 듯
8. seq 상에서는 거리가 멀어보이는 두 유전자 또는 element지만 실제로는 거리가 가깝다
	1. = enhancer의 기능을 가져올 수 있다.
9. Super enhancer hijacking gene
	1. unique  contribution?
10. Do make a summery → 요약하자면… 좀 인상적인 문장이다.
11. Vibalencing ?
12. **pericentromeric heterochromatin**
13. Binding motif
14. Split zinc finger allow _grab other dna?_
15. KRAS → 암환자에게서 흔히 나타나는 유전자 변이
16. **subtype switching model**
17. phase seperation => 상분리
18. RSF KO → no [[Cohesin complex|Cohesin]] 

# day 2

1. Electronical change 
2. putRNA
	1. Anti termination/pausing RNA
	2. Back track pause
	3. RNA hairpin pause
3. Triple helix structure
4. σ<sup>70</sup>-bounded putEC showed an RNA duplex in exit channel.
5. RNA folding → Anti termination 
6. No RNA folding → terminated
7. AI based protein structure modeling.
	1. The 3D shape of pretein is determind by its amino acide sequence.
8. complementary mutation
9. protein interaction.
	1. protein function
10. paired MSA
11. Yeast interactome
12. Protein-NA complex prediction

Award lecture → RNA termination / Song et al, nat commun, 2022. 
1. RNA를 합성할 때 RNA polymerase는 비교적 고정이 되어 있다.
	1. DNA가 움직이는 것이 맞고, 사실 교과서가 잘못된 것이다.
2. Termination = RNA release
	1. RNA 합성을 위해서는 RNA, DNA, polymerase가 결합하고 있어야 하는데, termination 단계에서는 이 상태가 유지되지 못하기 때문에 RNA 합성이 종료된다.
	2. DNA + RNA + pol이 다 분리된 경우 → Decomposing termination 
	3. RNA만 분리된 경우 → Recycling termination
3. push and pull termination 
	1. Four stage transcription cycle
	2. translation의 경우 init, elong, termination, ribosome recycling 4단계인데, transcription은 recycleing을 제외한 3개 단계밖에 알려져 있지 않다.
4. Transcription model 
	1. Catch-up model
		1. recycling termination
		2. Decompose termination
	2. Stand-by model (AKA allosteric model)
		1. decomposing
	3. Pho free termination
	4. Decomposing
	5. 아래로 갈수록 termination 속도가 느리다. (0.2분~ 9분)
5. 어떤 특정 모델이 정답인 것이 아니라 대부분의 모델이 작동한다
	1. 심지어 한번에 하나씩 작동하는 것이 아니라 여러 매커니즘이 동시에 작동하는 *Unified  model*이라는 것도 있다.

1. Non-genetic ?? ← 무슨 맥락에서 쓴건지 모르겠음
2. cfDNA = cell free DNA
3. Bisulfite conversion 
4. End motif
5. Biopsies(생검)
6. cfDNA methlation
7. targeted sequencing
8. Fatal DNA vs Shared DNA
9. cfDNA fragmentomics
	1. 프리즘처럼 분류할 수 있는 성분 6개가 있다. 
		1. 4mer motif
	2. 4~6 new cutting signiture
	3. fragment pattern이 있다.
10. 장기마다 mitochondria 수가 다르다.
11. ECC → Extracellular circular cDNA

1. 4.5SH
2. highly abandunt ncRNA
3. Knock out is lethal = essential
	1. Devreased proliferation 
	2. Cell number is slow down
4. RNA-seq
	1. rMATs → for alternative slicing?
5. 4.5SH KO
	1. “Toxic exon inclasion”
	2. protein expression ↓
6. 4.5SH가 잘못된 exon 인식을 막아준다.
7. 4.5SH는 exon skipping과 연관된 lncRNA
8. 이것은 effecter binding site와 sequence를 인식하는 부분이 나뉘어 있기 때문에, programable하다.
9. Can we make programable exon skipping inducer?
	1. 4.5SH chimera RNA → work!
10. Allele-specific CRISPR genome editing with single-base precision.
11. “Gene drive” demonstrated in Yeast?

1.                       Naive ESC ↔ Prime ESC
2. Self renewal         ↑                    ↓  
3. Differentiation     ↓                    ↑
4. → 분화에 적극적이지 않기 때문에 Naive하다고 분류된다고 생각하면 될 듯?
5. 이 두 종류의 ESC는 dynamic하게 stage가 나뉘어지고, Prime ESC 상태에서 분화가 일어나면 Pluripotency를 잃으면서 Pluripotency exit이 일어난다.
	1. Molecular barrier? → [ZBTB12 is a molecular barrier to dedifferentiation in human pluripotent stem cells | Nature Communications](https://www.nature.com/articles/s41467-023-36178-9)
	2. = ZBTB12, Master repressor of pluripotency
6. Nano-CAGE-seq → RNA의 5’ cap 부분만 sequencing하는 기술
	1. Transciption start site를 mapping 할 수 있음.