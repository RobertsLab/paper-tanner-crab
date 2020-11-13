## `analyses` directory contents: 

### [`BLAST-to-GOslim`](https://github.com/RobertsLab/paper-tanner-crab/tree/master/analyses/BLAST-to-GOslim)       
- [Blastquery-GOslim.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/BLAST-to-GOslim/Blastquery-GOslim.tab)       
Table from [notebooks/transcriptomev3.1-BLAST-to-GOslim.ipynb](https://github.com/RobertsLab/paper-tanner-crab/blob/master/notebooks/transcriptomev3.1-BLAST-to-GOslim.ipynb) from transcriptome v 3.1.    
- [GOslim-P-pie.txt](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/BLAST-to-GOslim/GOslim-P-pie.txt)      
Text file of GOslim terms from transcriptome v 3.1 with counts. To be used to create GOslim pie for paper. GOslim-P-pie.txt was create in this jupyter notebook: [notebooks/transcriptomev3.1-BLAST-to-GOslim.ipynb](https://github.com/RobertsLab/paper-tanner-crab/blob/master/notebooks/transcriptomev3.1-BLAST-to-GOslim.ipynb)           
- [GOslim-pie-transcriptome-v3.1.pdf](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/BLAST-to-GOslim/GOslim-pie-transcriptome-v3.1.pdf)     
.pdf of the GOslim pie from transcriptome v 3.1 create in this R script: [scripts/GOslim-pie-transcriptome-v3.1.Rmd](https://github.com/RobertsLab/paper-tanner-crab/blob/master/scripts/GOslim-pie-transcriptome-v3.1.Rmd)      
- [_blast-sep.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/BLAST-to-GOslim/_blast-sep.tab)    
From [notebooks/transcriptomev3.1-BLAST-to-GOslim.ipynb](https://github.com/RobertsLab/paper-tanner-crab/blob/master/notebooks/transcriptomev3.1-BLAST-to-GOslim.ipynb). Nicely separated version of the `blast` output from transcriptome v 3.1      
- [allterms.GOslim-pie-transcriptome-v3.1.pdf](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/BLAST-to-GOslim/allterms.GOslim-pie-transcriptome-v3.1.pdf)       
PDF of GOslim pie using all terms from the transcriptome v 3.1, including those less descriptive terms like "other biological processes" in order to make the pie slices more accurate.    
- [transcriptome-stress-genes.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/BLAST-to-GOslim/transcriptome-stress-genes.tab)         
Table of stress response genes from transcriptome v 3.1 according to the GOslim term "stress response". 

## [DAVID-outputs](https://github.com/RobertsLab/paper-tanner-crab/tree/master/analyses/DAVID-outputs)    
#### [`single-crab-genes`](https://github.com/RobertsLab/paper-tanner-crab/tree/master/analyses/DAVID-outputs/single-crab-genes):       
`DAVID` output files from the single crab genes over time heatmap clusters (**Fig. 3**)     
6 clusters, one file per clusters. Clusters 5 and 6 are very small compared to the other 4, and as such are not discussed in the paper.    
#### [`temp-contrast-DEGs`](https://github.com/RobertsLab/paper-tanner-crab/tree/master/analyses/DAVID-outputs/temp-contrast-DEGs):
`DAVID` output files from (**Fig. 2**) for the first three clusters. The fourth cluster didn't have any `DAVID` results. 


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

### [`pheatmap`](https://github.com/RobertsLab/paper-tanner-crab/tree/master/analyses/pheatmap)          
- [tempinfluenced-infectionDEGs-heatmap.pdf](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/pheatmap/tempinfluenced-infectionDEGs-heatmap.pdf)        
Heatmap of infection DEGs that are influenced by temperature treatment. Annotated cluster row, and sample annotations. Created in this Rmd: [scripts/heatmaps-4libraries.Rmd](https://github.com/RobertsLab/paper-tanner-crab/blob/master/scripts/heatmaps-4libraries.Rmd)      



