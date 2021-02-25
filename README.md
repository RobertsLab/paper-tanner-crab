# paper-tanner-crab    

[![DOI](https://zenodo.org/badge/287077986.svg)](https://zenodo.org/badge/latestdoi/287077986)

Repository for scripts, notebooks, data, and analyses associated with the paper entitled:    

**Characterization of the gene repertoire and environmentally driven expression patterns in Tanner crab (_Chionoecetes bairdi_)**    

Grace Crandall<sup>1</sup>, Pamela C. Jensen<sup>2</sup>, Sam White<sup>1</sup>, Steven Roberts<sup>1</sup>

<sup>1</sup> School of Aquatic and Fishery Sciences, University of Washington, Seattle, Washington 98105, United States          
<sup>2</sup> Resource Assessment and Conservation Engineering Division, Alaska Fisheries Science Center, National Marine Fisheries Service, NOAA, 7600 Sand Point Way NE, Seattle, WA 98115, United States

### For broader background information on this project, visit [RobertsLab/project-crab](https://github.com/RobertsLab/project-crab)

# Directory contents    

# [analyses](https://github.com/RobertsLab/paper-tanner-crab/tree/master/analyses)     

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


### [`DAVID-outputs`](https://github.com/RobertsLab/paper-tanner-crab/tree/master/analyses/DAVID-outputs)       
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

---

# [data](https://github.com/RobertsLab/paper-tanner-crab/tree/master/data)       

- [cbai_transcriptome_v3.1.zip](https://github.com/RobertsLab/paper-tanner-crab/blob/master/data/cbai_transcriptome_v3.1.zip)    
.zip of the transcriptome (v 3.1) used as the basis for differential expressoin analyses and characterization of crab response to temperature and infection with _Hematodinium_        
- [uniprotKB-transcrblast3.1-GO.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/data/uniprotKB-transcrblast3.1-GO.tab)    
Table of the uniprot Gene Ontology that is associated with the Trinity IDs from transcriptome v 3.1. Used in [/scripts/get-stress_response-genes-transcriptome.Rmd)](https://github.com/RobertsLab/paper-tanner-crab/blob/master/scripts/get-stress_response-genes-transcriptome.Rmd) to create [/supplemental-material/Supp04-transcriptomev3.1-blast-uniprotGO.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/supplemental-material/Supp04-transcriptomev3.1-blast-uniprotGO.tab). 

---

# [notebooks](https://github.com/RobertsLab/paper-tanner-crab/tree/master/notebooks)    

### [`kallisto`](https://github.com/RobertsLab/paper-tanner-crab/tree/master/notebooks/kallisto)    
Directory containing directories for each library that has output files from `kallisto`.   
- [178_ambient_infected_0](https://github.com/RobertsLab/paper-tanner-crab/tree/master/notebooks/kallisto/178_ambient_infected_0)      
Output files from `kallisto` for library 178 - individual crab, ambient, infected, Day 0. Jupyter notebook: [notebooks/kallisto-individual-crab.ipynb](https://github.com/RobertsLab/paper-tanner-crab/blob/master/notebooks/kallisto-individual-crab.ipynb)       
- [359_ambient_infected_2](https://github.com/RobertsLab/paper-tanner-crab/tree/master/notebooks/kallisto/359_ambient_infected_2)        
Output files from `kallisto` for library 359 - individual crab, ambient, infected, Day 02. Jupyter notebook: [notebooks/kallisto-individual-crab.ipynb](https://github.com/RobertsLab/paper-tanner-crab/blob/master/notebooks/kallisto-individual-crab.ipynb)      
- [kallisto/380822_cold_uninfected](https://github.com/RobertsLab/paper-tanner-crab/tree/master/notebooks/kallisto/380822_cold_uninfected)     
Output files from `kallisto` for library 380822 - cold, uninfected from Day 2. Jupyter notebook: [notebooks/kallisto-4libraries.ipynb](https://github.com/RobertsLab/paper-tanner-crab/blob/master/notebooks/kallisto-4libraries.ipynb)     
- [kallisto/380823_cold_infected](https://github.com/RobertsLab/paper-tanner-crab/tree/master/notebooks/kallisto/380823_cold_infected)     
Output files from `kallisto` for library 380823 - cold, infected from Day 2. Jupyter notebook: [notebooks/kallisto-4libraries.ipynb](https://github.com/RobertsLab/paper-tanner-crab/blob/master/notebooks/kallisto-4libraries.ipynb)           
- [kallisto/380824_warm_uninfected](https://github.com/RobertsLab/paper-tanner-crab/tree/master/notebooks/kallisto/380824_warm_uninfected)     
Output files from `kallisto` for library 380824 - warm, uninfected from Day 2. Jupyter notebook: [notebooks/kallisto-4libraries.ipynb](https://github.com/RobertsLab/paper-tanner-crab/blob/master/notebooks/kallisto-4libraries.ipynb)            
- [kallisto/380825_warm_infected](https://github.com/RobertsLab/paper-tanner-crab/tree/master/notebooks/kallisto/380825_warm_infected)     
OUtput files from `kallisto` for library 380825 - warm, infected from Day 2. Jupyter notebook: [notebooks/kallisto-4libraries.ipynb](https://github.com/RobertsLab/paper-tanner-crab/blob/master/notebooks/kallisto-4libraries.ipynb)    
- [463_ambient_infected_17](https://github.com/RobertsLab/paper-tanner-crab/tree/master/notebooks/kallisto/463_ambient_infected_17)      
Output files from `kallisto` for library 463 - individual crab, ambient, infected, Day 17. Jupyter notebook: [notebooks/kallisto-individual-crab.ipynb](https://github.com/RobertsLab/paper-tanner-crab/blob/master/notebooks/kallisto-individual-crab.ipynb)     


### Notebooks:     
- [kallisto-4libraries.ipynb](https://github.com/RobertsLab/paper-tanner-crab/blob/master/notebooks/kallisto-4libraries.ipynb)       
Notebook for getting gene count data for the 4 libraries (380822, 380823, 380824, and 380825) to use in `DESeq2` from transcriptome v 3.1.      
- [kallisto-individual-crab.ipynb](https://github.com/RobertsLab/paper-tanner-crab/blob/master/notebooks/kallisto-individual-crab.ipynb)          
Notebook for getting count matrix for the individual crab RNAseq from transcriptome v 3.1 (individual RNAseq libraries: 178, 359, and 463).           
- [transcriptomev3.1-BLAST-to-GOslim.ipynb](https://github.com/RobertsLab/paper-tanner-crab/blob/master/notebooks/transcriptomev3.1-BLAST-to-GOslim.ipynb)   
Notebook for getting transcriptome v 3.1 `blast` output to Goslim terms.       

---

# [scripts](https://github.com/RobertsLab/paper-tanner-crab/tree/master/scripts)

- [DESeq.Rmd](https://github.com/RobertsLab/paper-tanner-crab/blob/master/scripts/DESeq.Rmd)     
Rmd to use `DESeq2` with the count matrix for the 4 libraries (380822, 380823, 380824, 380825).      
- [GOslim-pie-transcriptome-v3.1.Rmd](https://github.com/RobertsLab/paper-tanner-crab/blob/master/scripts/GOslim-pie-transcriptome-v3.1.Rmd)       
Rmd to create a pie chart of GOslim terms with counts from transcriptome v 3.1.      
- [get-stress_response-genes-transcriptome.Rmd](https://github.com/RobertsLab/paper-tanner-crab/blob/master/scripts/get-stress_response-genes-transcriptome.Rmd)       
Rmd to get the list of trinity IDs from transcriptome v 3.1 that fall undert the GOslim term "Stress Response".     
- [heatmaps-4libraries.Rmd](https://github.com/RobertsLab/paper-tanner-crab/blob/master/scripts/heatmaps-4libraries.Rmd)       
Rmd to create heatmaps using `pheatmap` for DEGs for the 4 libraries.       
- [heatmaps-DEGs_in-singlecrab_over-time.Rmd](https://github.com/RobertsLab/paper-tanner-crab/blob/master/scripts/heatmaps-DEGs_in-singlecrab_over-time.Rmd)      
_Rmd to create a heatmap of the temperature-influenced infection DEGs in the single crab ... double check what this Rmd is.._      
- [heatmaps-single_crab-over-time.Rmd](https://github.com/RobertsLab/paper-tanner-crab/blob/master/scripts/heatmaps-single_crab-over-time.Rmd)       
Rmd to create heatmap of the contigs in the single crab over the three time points.      
- [tempdegs-individualcrab.Rmd](https://github.com/RobertsLab/paper-tanner-crab/blob/master/scripts/tempdegs-individualcrab.Rmd)        
Rmd to `join` the cluster heatmap information from **Fig. 2** in the manuscript with the cluster heatmap information from the heatmap of single crab genes over time. Purpose is to have a file that includes the cluster assignments for both heatmaps in order to find the temperature-influenced infection DEGs in the individual crab to get an idea of patterning of expression at the individual level over time. 

---

# [supplemental-material](https://github.com/RobertsLab/paper-tanner-crab/tree/master/supplemental-material)

- [Supp01-sample-list_pool-RNAseq.csv](https://github.com/RobertsLab/paper-tanner-crab/blob/master/supplemental-material/Supp01-sample-list_pool-RNAseq.csv)       
Table containing metadata to the sample level for the RNAseq libraries.

- [Supp02-RNAsequ-libraries.csv](https://github.com/RobertsLab/paper-tanner-crab/blob/master/supplemental-material/Supp02-RNAsequ-libraries.csv)         
Table containing descriptions of the pooled RNAseq libraries.

- [Supp03-cbai_transcriptome_v3.1.zip](https://github.com/RobertsLab/paper-tanner-crab/blob/master/supplemental-material/Supp03-cbai_transcriptome_v3.1.zip)     
Compressed _C. bairdi_ assembled transcriptome, with non-_Alveolata_ taxonomic filter.

- [Supp04-transcriptomev3.1-blast-uniprotGO.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/supplemental-material/Supp04-transcriptomev3.1-blast-uniprotGO.tab)         
Table of the _C. bairdi_ transcriptome BLAST results with uniprot/swissprot and gene ontology information.      

Columns are:   
`Trinity_ID` - contig ID from Trinity assembly     
`swissprot` - swissprot     
`uniprot_acc_ID` - uniprot accession ID for the contig  
`gene_id` - gene ID    
`pident` - percentage of identical matches      
`length` -  alignment length           
`mismatch` - number of mismatches        
`gapopen` - number of gap openings    
`qstart` - start of alignment in query     
`qend` - end of alignment in query      
`sstart` - start of alignment in subject       
`send` - end of alignment in subject     
`evalue` - expect value      
`bitscore` - Bit score     
`Entry.name` - entry name       
`Status` - reviewed or not        
`Protein.names` - protein names for contig     
`Gene.names` - gene names for contig       
`Ogranisms` - taxonomic organisms       
`Length` - length             
`Gene.Ontology.biological.process` - biological process gene ontology            
`Gene.ontology.cellular.component` - cellular component gene ontology     
`Gene.ontology.GO` - GO terms              
`Gene.ontology.molecular.function` - molecular function gene ontology           
`Gene.ontology.IDs` - gene ontology IDs         


- [Supp05-transcriptome-stress-genes.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/supplemental-material/Supp05-transcriptome-stress-genes.tab)    
Table of the _C. bairdi_ transcripts that fell under the GOslim term "Stress response". 

- [Supp06-infection-temp-DEGs-counts_annot.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/supplemental-material/Supp06-infection-temp-DEGs-counts_annot.tab)        
Table of the differentially expressed contigs between infected and uninfected crab taking temperature difference into account (decreased vs. elevated) at Day 2 (408 DEGs), including library count data and uniprot/swissprot and gene ontology information.

- [Supp07-contrasttemp_DEGs-clusters-annot.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/supplemental-material/Supp07-contrasttemp_DEGs-clusters-annot.tab)       
Table of a subset of the above 408 DEGs that are just the contigs directly influenced by temperature - 123 total. Table includes library count data, cluster assignment as seen in **Fig. 2**, and uniprot/swissprot and gene ontology information. 

- [Supp08-single_crab-clusters-blast-GO.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/supplemental-material/Supp08-single_crab-clusters-blast-GO.tab)          
Table containing the count data for the single crab RNAseq libraries over time, with the cluster assignments as shown in **Fig. 3**, along with uniprot/swissprot and gene ontology information 

- [Supp09-temp-influenced-infectionDEGs-singlecrab-overtime.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/supplemental-material/Supp09-temp-influenced-infectionDEGs-singlecrab-overtime.tab)       
Table combining Supplemental tables 07 and 08. Allows for finding the 123 infection DEGs that are influenced by temperature treatment in the individual crab over time. 
