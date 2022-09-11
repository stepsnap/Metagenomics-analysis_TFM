# Metagenomics-analysis_TFM

This is the script used for the downstream analysis that allowed to analyze the results from nf-core ampliseq pipeline. 

1. The ampliseq pipeline returned different folder based on the different steps performed. In this path : 
qiime2/rel_abundance_tables/rel-table-7.tsv you can find the relative abundance table that we used for our analysis.
2. The first script contains the code for the first cohort analysis (taxonomy profile, Fusobacterium detection and diversity analysis)
3. The second script contains the code for the second cohort analysis (taxonomy profile, Fusobacterium detection and diversity analysis)
4. The third scipt contains the code for the third cohort analysis (Taxonomy profile and Fusobacterium detection)
5. In the picrust folder we can find the functional analysis divided based on the EC, GO and MetaCyc analysis.
6. The fourth script contains the code for the functional analysis study.
7. The LDA analysis was performed by using the Galaxy online tool. The manual is available at this link (https://huttenhower.sph.harvard.edu/lefse/)
