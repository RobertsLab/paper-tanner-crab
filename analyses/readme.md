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

## [`DAVID-outputs`](https://github.com/RobertsLab/paper-tanner-crab/tree/master/analyses/DAVID-outputs)    
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

### [`kallisto-single_crab_over_time`](https://github.com/RobertsLab/paper-tanner-crab/tree/master/analyses/kallisto-single_crab_over_time)     
Output files from the jupyter notebook to get gene count data from the individual crab RNAseq libraries for visualization. Jupyter notebook: [notebooks/kallisto-individual-crab.ipynb](https://github.com/RobertsLab/paper-tanner-crab/blob/master/notebooks/kallisto-individual-crab.ipynb)    
- [kallisto-single-crab.isoform.TMM.EXPR.matrix](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/kallisto-single_crab_over_time/kallisto-single-crab.isoform.TMM.EXPR.matrix)      
One of the files from `kallisto`.     
- [kallisto-single-crab.isoform.TPM.not_cross_norm](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/kallisto-single_crab_over_time/kallisto-single-crab.isoform.TPM.not_cross_norm)    
One of the files from `kallisto`.     
- [kallisto-single-crab.isoform.TPM.not_cross_norm.runTMM.R](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/kallisto-single_crab_over_time/kallisto-single-crab.isoform.TPM.not_cross_norm.runTMM.R)    
One of the files from `kallisto`.      
- [kallisto-single-crab.isoform.counts.matrix](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/kallisto-single_crab_over_time/kallisto-single-crab.isoform.counts.matrix)        
Count matrix for the 3 libraries of the individual crab over time. Used in this Rmd to visualize counts: [scripts/heatmaps-single_crab-over-time.Rmd](https://github.com/RobertsLab/paper-tanner-crab/blob/master/scripts/heatmaps-single_crab-over-time.Rmd).  

### [`pheatmap`](https://github.com/RobertsLab/paper-tanner-crab/tree/master/analyses/pheatmap)     
- [contrast-tempDEGs_singlecrab-cluster-blast-go.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/pheatmap/contrast-tempDEGs_singlecrab-cluster-blast-go.tab)       
Table of the temperature-influenced infection DEGs that are present in the single crab over time (**Fig. 3**) with cluster assignment, uniprot/swissprot and gene ontology information. Of the 123 temperature-influenced infection DEGs, 94 were present in the individual crab over time.      
- [contrasttemp_DEGs-clusters-annot.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/pheatmap/contrasttemp_DEGs-clusters-annot.tab)       
Table of the 123 temperature-influenced infection DEGs with cluster assignemnt from **Fig. 2** with `BLAST`- uniprot/swissprot gene ontology annotation.        
- [individual-crab-over-time.pdf](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/pheatmap/individual-crab-over-time.pdf)       
PDF of **Fig. 3** <-- single crab RNAseq contigs over time heatmap.      
- [infection-temp-DEGs-counts_annot.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/pheatmap/infection-temp-DEGs-counts_annot.tab)      
Table of the 408 differentially expressed contigs between infection statuses while taking temperature treatments into account. Table includes library counts, `BLAST`-uniprot/swissprot and gene ontology annotation.       
- [infection-tempDEGs_singlecrab-cluster-blast-go.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/pheatmap/infection-tempDEGs_singlecrab-cluster-blast-go.tab)       
Table of the _what is this...._       
- [infectionDEGs_singlecrab-clust-blast-go.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/pheatmap/infectionDEGs_singlecrab-clust-blast-go.tab)         
_What is this...?_        
- [single_crab-clusters-blast-GO.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/pheatmap/single_crab-clusters-blast-GO.tab)      
Table of the **Fig. 3** single crab RNAseq with cluster assignment, `BLAST`-uniprot/swissprot and gene ontology annotations.       
- [temp-influenced-infectionDEGs-singlecrab-overtime.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/pheatmap/temp-influenced-infectionDEGs-singlecrab-overtime.tab)        
Table of the 123 temperature-influenced infection DEGs with the cluster assignments for both **Fig. 2** and **Fig. 3**. 94 of the 123 DEGs were present in the individual crab (**Fig.3**). so the column for the cluster assigments for **Fig. 3** has some "NA"s.       
- [tempinfluenced-infectionDEGs-heatmap.pdf](https://github.com/RobertsLab/paper-tanner-crab/blob/master/analyses/pheatmap/tempinfluenced-infectionDEGs-heatmap.pdf)     
PDF of **Fig. 2** <-- 123 temperature-influenced infection DEGs heatmap. Created in this Rmd: [scripts/heatmaps-4libraries.Rmd](https://github.com/RobertsLab/paper-tanner-crab/blob/master/scripts/heatmaps-4libraries.Rmd)              

    

