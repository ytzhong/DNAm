In this folder, we present the weights trained from the Framingham Heart Study with a total sample size of 1,303. 

Files are:
1. CV_full_weights_DNAm_part0.tar.gz - CV_full_weights_DNAm_part5.tar.gz contains weights trained from CVs-only models
2. RV_full_weights_DNAm_part0.tar.gz - RV_full_weights_DNAm_part26.tar.gzcontains weights trained from RVs-only models

After unziping the files, there are multiple .RDat files with the names of genes (official symbol). 

In each .RDat file, there are three components:
1. bimfile: contains the SNP location (hg19), reference allele, and alternative allele
2. R2: contains R based on elastic net models cross-validated with lambda.1se and lambda.min and their corresponding number of genetic variants included
3. wgt.matrix: contains weights trained by elastic net regession cross-validated with lambda.1se and lambda.min

Further details of the models and dataset are described in:
Yang T, Wei P, Pan W. Integrative analysis of multi-omics data for discovering low-frequency variants in association studies for low-density lipoprotein cholesterol levels (unpublished work)

Stay healthy!

TZ

2020.4.7
