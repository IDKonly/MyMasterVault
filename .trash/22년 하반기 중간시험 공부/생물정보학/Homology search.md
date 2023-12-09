# Term

## Sequence alignment
- A method to find where a difference is by aligning two or more nucleotide or amino acid sequences
	- Gap
	- Match
	- Mismatch

## Homology search
- Searching for sequences that are identical or like my own sequence in a database
	- in homology search a test sequences is compared to all of the different sequences in a large database and those sequences in the database with the closest match, or most homology, are reported.


# Sequence Alignment
1. Pairwise alingment / Multiple alignment
2. Which one is better alignment?
	1. 당연하게도 match가 많고 mismatch와 gap이 적은게 좋다
3. Global alignment / Local alignment
	1. 글로벌은 일단 양쪽 끝을 맞추고 최대한 안을 채워넣는 식 (그래서 갭이 많다)
	2. 로컬은 아무튼 가장 잘 맞는 부분을 찾는다. (갭이 상대적으로 적다)
4. **Global alignment**
	1. basic concept
		1. An attempt is made to align the entire sequence (end to end)
		2. It contains all letters from both the query and target sequences
		3. If two sequences hace similar length of nt(nucleotide) and contents, thet are suitable for global alignment. 
		   -> **비슷한 길이와 유전자 서열을 가지고 있다면 global alignment가 적합하다.**
		4. It is suitable for aligning two closely related seqeunce 
		   -> **두개의 밀접하게 관련이 있는 시퀀스를 찾기에 적합하다**
		5.  For homologous genes like comparing two genes with same of silmilar function
		6. Needleman-Wunsch algorithm <- 점수 부여하는 알고리즘
	2. Pairwise sequence alignment
5. **Local alignment**
	1. basic concept
		1. it finds local regions with the highest level of similarity between two sequences
		2. It aligns a substring of the query sequence to one of the target sequence.
		3. If it finds a high level of matches, it does not consider the alignment of rest of the sequence regions.
		4. it suitable for aligning more divergent or distantly related sequences. 
		   -> **더 멀리 떨어져있는 관계의 유전자를 찾기에 적합함**
		5. It used for finding out conserved patterns in DNA sequences of conserverd domains or motifs in two proteins. 
		   -> **주로 도메인이나 모티프를 찾을때 쓴다**
		6. Smith-Waterman algorithm <- 점수 부여하는 알고리즘
	2. BLAST

# Score matrix
1. Match, mismatch, gap
	1. 맞으면 점수에 더하고 틀리면 점수를 빼고... 갭은 어떻게?
2. Gap penalty
	1. Constant
		1. a fixed negative score is given to every gap, regardless of its length
		   -> 모든 gap에 동일한 패널티를 부여하겠다
	2. Linear
		1. the linear gap penalty considers the length
		   -> 길이를 고려해서 패널티를 먹이겠다
	3. Affine 
		1. A + B x length (A: gap open panelty, B: gap extension panelty)
		   -> 갭구간이 생기는 패널티와 길이에 따른 패널티를 각각 먹이겠다
3. Substitution matrix
	1. used to score aligned positions, usually of ammino acids
4. Point accepted mutation (PAM) matrix
	1. PAM(n) : the number of mutations per 100 amino acids
	2. One PAM of evolution means 1% of the residues/bases have chainged, averaged over all 20 amino acids
	3. it was devleoped by making global alignments between known closely related sequences.
	4. PAM matrix values - log-odds
		1. log odds ratio = $$log_2(P(observed)/P(expected))$$
	5. PAM250 matrix
		1. +값이 얼마나 많이 나오느냐에 따라서 변이가 진행되는지 진행되지 않는지를 판단할 수 있다.
		2. 결국 값이 변하는게 자연스러운 일인지 아닌지를 판단하는 방법.
		3. 변하기 어려운 것은 -, 변하기 쉬운(자연스러운) 것은 + 값을 부여한다.
5. BLOSUM matrix
	1. based on database of ungapped local alignments(BLOCKS)
	2. BLOSUM nmber indicates the percent indentity level of sequences in the alignment. forexample, for BLOSUM62 sequences with approximately 62% identity were counted
	3. BLOSUM62
6. PAM vs BLOSUM
	1. PAM은 차별성비교이고 BLOSUM은 유사성비교이다.

# Markov process
1. Hidden Markov model
	1. the likelihood of the next "state" depends only on the current state.
	   -> 현재 상태와 과거 특정 상태의 차이를 알고 있다면, 다음 상태도 알 수 있다.
	2. 즉, 다음이 성립한다.$$PAM1^{250}=PAM250$$
2. 시퀀스의 갯수가 늘어나면 늘어날수록 2<sup>n</sup>으로 처리갯수가 늘어난다.
	1. 즉, 빅오가 감당불가능할정도로 커져서 이 알고리즘으로는 힘들다.
	2. 그래서 테이블을 짜서 최단거리를 계산한다.
		1. Dynamic programing algorithm(동적 프로그래밍 알고리즘)
3. Dynamic programing algorithm(동적 프로그래밍 알고리즘)
	1. 대각방향이라면 해당 위치의 점수를 더하고, 옆이나 아래방향이라면 gap panelty를 더한다.

# Homology and similarity
1. Whem the comparing two seqeunces or structures, the terms of similarity or homology are often used interchangeably to indicate that there is a "close" relation ship between the comparison object.
	1. 비슷한 정도를 뜻하지만 사전적 의미는 살짝 다르다.
	2. homology = 공통 조상을 가진다
	3. similarity = 정량적으로 비슷하다. 이유불문.

# FASTA algorithm
1. a major cfous of the package is the calculation of accurate similarity statistics, so that biologists can judge whether an alignment is likely to have ccurred by chance, of whether it can be to infer homology
2. the FASTA program is its classic version, is a heuristic program able to search the global seqeunce similarrity. Two variants, LFASTA PLFATA, can search for locla seqeunce similarity
3. The FASTA package is available from fasta.bioch.virginia.edu
4. steps
	1. OFFSET definition
		1. ktup, word size = 1 or 2
	2. Evalution of Amino Acids substitution
	3. Join several initial regions
	4. Deletions and insertions evalution
5. algorithm
	1. 암튼 걸리는대로 다 찾는다
	2. 재평가(rescoring)
	3. 제일 말이 될 것 같은 선을 잘 이어서
	4. 합친다. 

# BLAST algorithm
1. Basic Local Alignment search tool
	1. BLAST is a heuristic pairwase alignment
2. Phase


# Computing E-value
1. Raw score
	1. 쿼리가 길고 매치가 잘 될 수록 잘 나옴
2. Bit score
	1. 표준화된 값
3. E-value
	1. 눈 감고 뽑기를 했을 때 나올 확률
4. P-value
	1. 연산을 거치면 p-velue와도 대응이 가능하

# BLAST
1. blastn
	1. nucleotide to nucleotide
2. blastp
	1. amino acid to amino acid
3. blastx
	1. translated NT to AA
4. blastn
	1. AA to translated NT
5. blastx
	1. translated NT to translated NT

# genetic code
- 종마다 code usage가 다르기 때문에, 이걸 설정해줘야 한다.
	- Translation table : 그걸 위해 만들어진 테이블