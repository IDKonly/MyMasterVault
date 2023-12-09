# Next Generation Sequencing(NGS)
1. Current NGS technology
	1. Illumina
		1. sequencing by Synthesisc
			1. library
			2. amplification on flowcell
			3. Sequencing by synthesis
		2. The flow cell design
			1. surface of flow cell coated with a lawn of oligo pairs
			2. contained environment
			3. No need for clean rooms
			4. Sequencing performed inside the flow cell
		3. 원리
			1. Randomly fragment genomic DNA and ligate adapters to both ends of the fragment
			2. Bind single-stranded fragments ramdomly to the inside surface of the flow cell channels
			3. Add unlabeled nucleotides and enzyme to initiate solid phase bridge amplification
			4. The enztme incorporates to build double stranded bridges on the solid phase substrate
			5. Denaturation leaves single stranded templates anchored to the substrate
			6. Several million dense clusters of double stranded DNA are generated in each channel of the flow cell.
			7. First chemistry cycle: to initiate the first sequencing cycle, add all four laveled reversivle terminators, primers and DNA polmerase enzyme to the flow cell.
			8. After laser excitation, capture the image ofemitted fluorescence from each cluster on the flow cell. record the identity of the first base for each cluster(~1000 copies per cluster).
		4. result
			1. FASTQ
				1. Label (메타데이터)
				2. 시퀀스
				3. Q scores(퀄리티)
			2. FASTA
				1. Label (메타데이터)
				2. 시퀀스
		5. paired-end sequencing
		6. 빠르게 / 짧고 많은 리드를 얻을 수 있다.
		7. 긴거를 읽기는 힘들다
	2. PacBio
		1. Detect fluorescence in dNTP incorporation
		2. 150,000 wells = reads / chip
		3. Mean read length: 10-25kb
		4. use SMRTbell adapter
		5. 원리
			1. generate amplicon
			2. ligate adaptors
			3. seqeunce
				1. CCS read -> +와 -가 번갈아가면서 읽는다
			4. data analysis
				1. HDF5
				2. convert FASTQ
	3. Oxford Nanopore
		1. detect electric current in passing pore
		2. 2048 nanopores / minion chip
		3. upto a million reads
		4. Mean read length:10~20kb
		5. Maximum read length:~1mb
		6. long, few reads
			1. good for large genome assembly
# Summary
1. Next-generation sequencing(NGS)
	1. the technology for sequencing millions of reads in a single experiment
2. Current NGS platforms
| name     | read length | Accuracy          | Price        | Application                    |
| -------- | ----------- | ----------------- | ------------ | ------------------------------ |
| Illumina | short       | Accurate          | cheap        | most application               |
| PacBio   | Long        | *High error rate* | Expensive    | Detecting structural variation |
| Nanopore | Ultra-long  | *High error rate* | Intermediate | "                              |
|          |             |                   |              |                                |
*befor error correction by computation*

## Terminology

-  Next generation Sequencing :
	- Next generation seqeuncing, or NGS, is a seqeuncing method where millions of seqeuncing reactions are carried out in parallel, increasing the sequencing throughput
- Reads :
	- The output of an NGS sequencing reaction. A read is a single uninterrupted seriess of nucleotides represention the sequence of the template
- Read length :
	- Teh length of each sequencing read. This variable is alwats represented as an average read length since individual reads have varying lengths.
- Coverage :
	- The numver of time a particular nucleotide is sequenced. Due to the error-prone sequencing reactions, random errors could occur. Therefore, 30x coverage is typically required to ensure each nucleotide sequence is accurate
- Paired-End sequencing :
	- Sequencing from both ends of a fragment while keeping track of the paired data. With this method the sequencing reaction will commence from one end of the fragment.
- Mate-paired reads :
	- A sample preparation step where large DNA fragments (~10kb) are circularized with an adapter sequence followed by degradation of the circular DNA. This method links DNA fragments that are seqaraed from each other by a certain distance and it is used in applications such as de novo assembly, structural variant detection, and identification of complex genomic rearrangements.
- Adapter : 
	- Unique sequences used to cap the end of a fragmented DNA. The adapter's functions are as follows: 1) allow hybtidization to solid surface; 2) provide priming location for both amplification and sequencing primers; and 3) provide barcoding for multiplexing different samples in the same run.
- Library :
	- A collection of DNA fragments with adapters ligated to each end. Library preparation is required before a sequencing run