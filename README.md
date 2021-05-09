# I-motif genomewide prediction
We predict genome wide i-motif using R. We predict i-motifs using three different linker length.      

  #### 1. Genomewide prediction of i-motif with 6 linker length
  #### 2. Genomewide prediction of i-motif with 5 linker length
  #### 3. Genomewide prediction of i-motif with 4 linker length
  
  All these linkers were predicted by hg38 assembly and R library(BSgenome.Hsapiens.UCSC.hg38).
# How to run the script?
We used iteration for running the script on all the chromosomes.
"seq<-bx$chr1" to "seq<-bx$chrx"  
And repeat this iteration for each chrromosome in R studio. 
