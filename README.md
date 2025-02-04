CFA SUBGRAPH PROCESSING:

Description: Analyzing four pattern types of gene-gene interaction in BRCA
There are 7 main modules:

Module01: Calculate the LogFC and Hazard ratio
Module02: Count the occurences of KIRC genes in three databases
Module03: Cancer driver gene (COSMIS database)
Module04: CFA calculation Avg and Weigthed Score Combination (using 11 combinations of the features)
Module05: Find TOP2 and BOTTOM2 from Weigthed Score Combination result
Module06: Calculate frequency item-ID TOP5 and BOTTOM5. It is chosen from the highest and lowest five ranked items-Id for each of the 11 combinations.
Module07: Calculate Jaccard index to Quantify the difference between the weighted SC and average SC
