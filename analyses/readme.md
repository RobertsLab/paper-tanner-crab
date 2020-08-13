## `analyses` directory contents: 

### [`BLAST-to-GOslim`](https://github.com/RobertsLab/paper-tanner-crab/tree/master/analyses/BLAST-to-GOslim)       
- [GOslim-P-pie.txt](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/BLAST-to-GOslim/GOslim-P-pie.txt)      
Text file of GOslim terms from transcriptome v 3.1 with counts. To be used to create GOslim pie for paper. GOslim-P-pie.txt was create in this jupyter notebook: [notebooks/transcriptomev3.1-BLAST-to-GOslim.ipynb](https://github.com/RobertsLab/paper-tanner-crab/blob/master/notebooks/transcriptomev3.1-BLAST-to-GOslim.ipynb)      
- [GOslim-pie-excel.pdf](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/BLAST-to-GOslim/GOslim-pie-excel.pdf)       
.pdf of the GOslim pie from transcriptome v 3.1 created in this excel file: [make-GOslim-pie-transcriptome-v3.1.xlsx](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/BLAST-to-GOslim/make-GOslim-pie-transcriptome-v3.1.xlsx)     
- [GOslim-pie-transcriptome-v3.1.pdf](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/BLAST-to-GOslim/GOslim-pie-transcriptome-v3.1.pdf)     
.pdf of the GOslim pie from transcriptome v 3.1 create in this R script: [scripts/GOslim-pie-transcriptome-v3.1.Rmd](https://github.com/RobertsLab/paper-tanner-crab/blob/master/scripts/GOslim-pie-transcriptome-v3.1.Rmd)      
- [_blast-sep.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/BLAST-to-GOslim/_blast-sep.tab)    
From [notebooks/transcriptomev3.1-BLAST-to-GOslim.ipynb](https://github.com/RobertsLab/paper-tanner-crab/blob/master/notebooks/transcriptomev3.1-BLAST-to-GOslim.ipynb). Nicely separated version of the `blast` output from transcriptome v 3.1      
- [make-GOslim-pie-transcriptome-v3.1.xlsx](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/BLAST-to-GOslim/make-GOslim-pie-transcriptome-v3.1.xlsx)     
Excel spreadsheet used to create the excel version of the GOslim pie chart for transcriptome v 3.1 

### [`DESeq2`](https://github.com/RobertsLab/paper-tanner-crab/tree/master/analyses/DESeq2)     
The files in this directory are from this Rmd: [scripts/DESeq.Rmd](https://github.com/RobertsLab/paper-tanner-crab/blob/master/scripts/DESeq.Rmd)    
- [DEGlist-contrast_temperature-counts.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/DESeq2/DEGlist-contrast_temperature-counts.tab)    
List of 123 DEGs associated with infection status that are influenced by temperature treatment. This list of DEGs includes gene counts from the 4 libraries.     
- [DEGlist-contrast_temperature.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/DESeq2/DEGlist-contrast_temperature.tab)   
List of 123 DEGs associated with infection status that are influenced by temperature treatment.      
- [DEGlist-infection-with-temp-counts.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/DESeq2/DEGlist-infection-with-temp-counts.tab)    
List of 408 DEGs associated with infection status while taking temperature treatment into account. These are not the list of genes influenced by temperature. This list of DEGs includes the gene count data for the fuor libraries.     
- [DEGlist-infection-with-temp.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/DESeq2/DEGlist-infection-with-temp.tab)      
List of 408 DEGs associated with infection status while taking temperature treatment into account.     
- [DEGlist-infectionONLY-counts.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/DESeq2/DEGlist-infectionONLY-counts.tab)     
List of 1343 DEGs comparing infection status. List includes count data from the four libraries.      
- [DEGlist-infectionONLY.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/DESeq2/DEGlist-infectionONLY.tab)       
List of 1343 DEGs comparing infection status. 

### [`kallisto-0812`](https://github.com/RobertsLab/paper-tanner-crab/tree/master/analyses/kallisto-0812)      
Output files from this jupyter notebook to get gene count data from the 4 libraries used for `DESeq2`. Jupyter notebook: [notebooks/kallisto-4libraries.ipynb](https://github.com/RobertsLab/paper-tanner-crab/blob/master/notebooks/kallisto-4libraries.ipynb)       
- [kallisto-0812.isoform.TMM.EXPR.matrix](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/kallisto-0812/kallisto-0812.isoform.TMM.EXPR.matrix)          
One of the files from `kallisto`.     
- [kallisto-0812.isoform.TPM.not_cross_norm](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/kallisto-0812/kallisto-0812.isoform.TPM.not_cross_norm)     
One of the files from `kallisto`.     
- [kallisto-0812.isoform.TPM.not_cross_norm.runTMM.R](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/kallisto-0812/kallisto-0812.isoform.TPM.not_cross_norm.runTMM.R)    
One of the files from `kallisto`.     
- [kallisto-0812.isoform.counts.matrix](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/kallisto-0812/kallisto-0812.isoform.counts.matrix)    
Count matrix for hte 4 libraries. Used in `DESeq2` Rmd: [scripts/DESeq.Rmd](https://github.com/RobertsLab/paper-tanner-crab/blob/master/scripts/DESeq.Rmd) 





