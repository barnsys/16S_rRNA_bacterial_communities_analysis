# 16S_rRNA_bacterial_communities_analysis
The set of scripts for programming language R for analyzing genetic and taxonomic diversity of bacterial communities received by metagenomic data of 16S rRNA

The repository contains four zip files with scripts and primary data for data processing.

1) Estimation of confidence intervals using the bootstrap method for the indexes of the diversity of the communities of Schennon and Simpson. Statistical analysis of the Schennon and Simpson indices.
Shenon_Simpson.zip
Contains files:
23.shared - table of the representativeness of the OTU of the species rank in the sample when analyzing the V2-V3 regions 16S rRNA
34.shared - table of the representativeness of the OTU of the species rank in the sample when analyzing the V3-V4 regions 16S rRNA
R_index.txt - script for data analysis

2) Assessing species richness in samples using indexes Chao1 and ACE
Chao1_ACE.zip
Contains files:
23.shared - table of the representativeness of the OTU of the species rank in the sample when analyzing the V2-V3 regions 16S rRNA
34.shared - table of the representativeness of the OTU of the species rank in the sample when analyzing the V3-V4 regions 16S rRNA
R_script_chao.txt - script for data analysis

3) Comparison of species diversity of communities at different levels of taxonomic organization (phylum, class, order, family) with the help of Bray-Curtis distance metric, Gower distance metric and Jaccard distance metric.
Taxon_diversity.zip
23.shared - table of the representativeness of the OTU of the species rank in the sample when analyzing the V2-V3 regions 16S rRNA
34.shared - table of the representativeness of the OTU of the species rank in the sample when analyzing the V3-V4 regions 16S rRNA
23.taxonomy - taxonomic identification of species level OTU for samples analyzed using the V2-V3 regions 16S rRNA
34.taxonomy - taxonomic identification of species level OTU for samples analyzed using the V3-V4 regions 16S rRNA
R_taxon.txt - script for data analysis

4) Comparison of the genetic diversity of the communities at the level of representative sequences for the OTU species of rank
Genetic_diversity.zip
Contains files:
23.fasta - representative sequences for the OTU species of rank for samples analyzed using the V2-V3 regions 16S rRNA
24.fasta - representative sequences for the OTU species of rank for samples analyzed using the V3-V4 regions 16S rRNA
23_34.fasta - the closest full-length 16S rRNA sequences for each representative sequence from both regions that founded in the SILVA 123 database
R_seq_analiz.txt - script for data analysis
