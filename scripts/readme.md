## `scripts` directory contents:

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
