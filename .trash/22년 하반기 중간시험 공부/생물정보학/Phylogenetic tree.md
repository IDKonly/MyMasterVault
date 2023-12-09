# Phylogenetic tree - 계통분류도
1. a model of evolutionary relationships - common ancestors and speciation events
2. Why build phylogenetic trees?
	1. to trace branch order of "taxa" (taxon = a gene, a speceis, a population, etc.)
	2. to understand the evolution of traits
	3. as part of a multiple sequence alignment algorithm

## Tree terminology
1. Rooted tree
	1. root node
	2. node
	3. branch, clade
		1. a group of organisms that are monophyletic
	4. terminal, tip, taxon
2. unrooted tree
3. Topology
	1. 형태가 좀 달라져도 실제적인 위치관계는 변하지 않는 것
4. cladogram : toplogy only
5. phylogram : no molecular clock
6. ultrametric tree : molecular clock
7. taxon/taxa
8. Operatonal taxonomic unit(OTU)
	1. 배양이 안되는 미생물을 만들어진 단위
	2. an operational definition used to classify groups of clesely related individuals
	3. OTUs of clusters with sequence similarity in the molecular level are widely accepted analtrical unit used in microbial ecology
	4. As set by the researcher, the threshold which is usually at 97% similarity determines the clustering of operational taxonomic

## how to root phylogenetic tree
1. unrooted
2. midpoint rooting
3. out group rooting

# Drawing the phylogenetic tree
1. tree makeing algorithm
	1. Distance-based method
		1. UPGMA
		2. Neighbor-joining
		3. calculating distance : P-distance, jukes-canter
	2. Character-based method
		1. Maximum likehood
		2. Maximum parsimony
		3. Bayesian inference
2. calculating distrance
	1. P-value를 구하고 나면 jukes-canter로 보정한다.

## Homoplasy
1. homology
	1. similar traits inherited from a common ancestor
2. homoplasy (convergent evolution)
	1. similar traits are not directly caused by common ancestry(covergent evolution)

## UPGMA and Neighbor-joining tree
1. UPGMA is an agglomerative hierarchical clustering method based on the average linkage method.
2. Whereas neighbor-joining tree is an iterative clustering method based on the minimum evolution criterion
3. UPGMA : a distance-based method (average linkage method)
	1. 정답에 가까운 값이나 말하는 바를 잘 나타내 줄 뿐 정확한 것은 아니다.
4. Neighbor-joining : a distance-based method
5. similarities between UPGMA and NJ tree
	1. UPGMA and neibor-joining tree are the two algorithms which build phylogenetic trees, taking a distance matrix as the input. generally, a distance matrix is a 2D matrix - an array that contains the pairwise distances of a set of points
	2. Teh resulting alignment scores of a set of realred protein or DNA seqeunces can be used as measures for the construction of the distance matrix
	3. Both are agglomerative(bottom-up) clustering methods
	4. They are faster methods which are computationally less expensive.
6. Differnce between UPGMA and NJ tree
	1. UPGMA refers to a straightforward approach for construction a rooted phylogenetic tree from a distance matrix while neighbor-joining tree refers to the new approach for constructing a phylogenetic tree, which is unrooted through a star tree.
	2. UPGMA algorithm requires the distances to be ultrametic while neighbor-joining tree algorithm requires the distances to be addictive

# other method for claculating distance
1. jukes-cantor : equal base frequencies, all substitutions eqully likely
2. Kimura 2-parameter : equal base frequencies, one transition rate and one transversion rate
3. Tamura-Nei : variavle vase frequencies, equla transversion rates, variable transition rates
4. Kimura 3-parameter : variable basse frequencies, equal transition rates, two transversion rates
5. general time reversible (GTR,nst = 6) : variable base frequencies, symmetrical substitution matrix

# Model for rate variation among sites
1. gamma distribution(G) L