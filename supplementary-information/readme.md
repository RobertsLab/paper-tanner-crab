## Supplemental material directory contents: 


- [S1-RNAsequ-libraries.csv](https://github.com/RobertsLab/paper-tanner-crab/blob/master/supplemental-material/Supp02-RNAsequ-libraries.csv)         
Table containing descriptions of the pooled RNAseq libraries.      

Column are:     
`Library_ID` - number assigned to the library. 11 total. All used to assemble transcriptome     
`Sequencing_ID` - number assigned to the pooled sample by the Northwest Genomics Center sequencing facility for library prep and RNAseq     
`Sample_Day` - day of the experiment that the samples that comprise the pool are from. Day 0, Day 2, or Day 17. Some are pooled across time and are "_combined_"    
`Infection_status` - infection status of the crab at the time of sampling. Some are pools of infected crab and some are pools of uninfected crab      
`Temperature_treatment` - temperature that the crab were held at at the time of sampling. Some are at decreased (4C), ambient (7.5C), or elevated (10C). some pools combine temperature treatments      
`Number_of_samples-crabs-in_pool` - the number of individuals that comprise the pooled sample that was sequenced 

- [S2-cbai_transcriptome_v3.1.zip](https://github.com/RobertsLab/paper-tanner-crab/blob/master/supplemental-material/Supp03-cbai_transcriptome_v3.1.zip)     
Compressed _C. bairdi_ assembled transcriptome, with non-_Alveolata_ taxonomic filter.

- [S3-transcriptomev3.1-blast-uniprotGO.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/supplemental-material/Supp04-transcriptomev3.1-blast-uniprotGO.tab)         
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


- [S4-transcriptome-stress-genes.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/supplemental-material/Supp05-transcriptome-stress-genes.tab)    
Table of the _C. bairdi_ transcripts that fell under the GOslim term "Stress response".      

Columns are:     
`Trinity_ID` - contig ID from Trinity assembly     
`GO_ID` -       
`GOslim` - 
`biological_process` -    
`swissprot` -    
`uniprot_acc_ID` - 
`gene_id` -     
`pident` - 
`length` - 
`mismatch` - 
`gapopen` - 
`qstart` - 
`qend` - 
`sstart` - 
`send` - 
`evalue` - 
`bitescore` - 
`Entry.name` - 
`Status` - 
`Protein_names` - 
`Gene.names` - 
`Organism` - 
`Length` - 
`Gene.ontology.biological.process` - 
`Gene.ontonlogy.cellular.component` - 
`Gene.ontology.GO` - 
`Gene.ontology.molecular.function` - 
`Gene.ontology.IDs` - 

- [S5-infection-temp-DEGs-counts_annot.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/supplemental-material/Supp06-infection-temp-DEGs-counts_annot.tab)        
Table of the differentially expressed contigs between infected and uninfected crab taking temperature difference into account (decreased vs. elevated) at Day 2 (408 DEGs), including library count data and uniprot/swissprot and gene ontology information.

- [S6-contrasttemp_DEGs-clusters-annot.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/supplemental-material/Supp07-contrasttemp_DEGs-clusters-annot.tab)       
Table of a subset of the above 408 DEGs that are just the contigs directly influenced by temperature - 123 total. Table includes library count data, cluster assignment as seen in **Fig. 2**, and uniprot/swissprot and gene ontology information. 

- [S7-single_crab-clusters-blast-GO.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/supplemental-material/Supp08-single_crab-clusters-blast-GO.tab)          
Table containing the count data for the single crab RNAseq libraries over time, with the cluster assignments as shown in **Fig. 3**, along with uniprot/swissprot and gene ontology information 

- [S8-temp-influenced-infectionDEGs-singlecrab-overtime.tab](https://github.com/RobertsLab/paper-tanner-crab/blob/master/supplemental-material/Supp09-temp-influenced-infectionDEGs-singlecrab-overtime.tab)       
Table combining Supplemental tables 07 and 08. Allows for finding the 123 infection DEGs that are influenced by temperature treatment in the individual crab over time. 

