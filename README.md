# EpiTS-embryoids
Single-cell RNA-seq analysis of embryoids for Girgin et al. 2021.

Data exploration (recommended)
Download the data from GEO, install R-studio and Seurat v3, and use the file ReExploreFromGEOdata.R for a quick dive into cell annotations and gene expression, and to be setup for further exploration in R.

Complete analysis reproduction (advanced users)
To reproduce the complete analysis, obtain the raw data from Girgin et al. 2021 (i.e. fastq files on SRA) as well as Pijuan-Sala et al. 2019 (used as a reference in vivo atlas). Download the input tables, cell-type classifier, and complete code, and run cellranger for alignment, velocyto for RNA splicing estimates, followed by CompleteAbInitioAnalysis/BrainGas* (parts 1, 2 and 3 in this order).
