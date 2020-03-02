# SCRUM Single Cell Bioinformatics Workshop
__Date:__ Wednesday, 4th March, 2020<br>
__Time:__ 10am-1pm
__Venue:__ Michael Smith Lecture Theatre<br>
__Pre-requisite:__ Basic understsanding of R & Rstudio

This workshop presents a step-by-step workflow of a single cell RNA-seq analysis. Please note we will be covering single cell and single nuclei RNA-sequencing (no ATAC or bulk). We will also show an app to visualise the data; however, the app only works in Windows and Mac.

Please follow the instructions below to setup your computer __before__ the start of the workshop:

1. Download `R 3.6.2` for Mac (https://cran.r-project.org/bin/macosx/) and for Windows (https://cran.r-project.org/bin/windows/base/). For installation continue with the default settings. When asked for the password, give the password of the machine.

2. Install `RStudio Desktop` (Free Version) from https://rstudio.com/products/rstudio/download/ 
  - If you are installing in Mac, then drag it to Application folder. Open it and if any change request comes then click open.
  - If RStudio wants to install git, then install it. 

3. Start RStudio

4. Install the following packages by pasting the following command in RStudio
```
install.packages(c('ggplot2', 'GGally','Rtsne','umap','tidyverse','factoextra','cluster'))
if(!requireNamespace("BiocManager", quietly = TRUE)) install.packages("BiocManager")
BiocManager::install(c("scater", "Seurat", "scran", "biomaRt", "org.Hs.eg.db", "dynamicTreeCut","ComplexHeatmap"))
```
5. Download/clone the SCRUM_single_cell_bioinformatics_workshop from https://github.com/fls-bioinformatics-core/SCRUM_single_cell_bioinformatics_workshop. We will be using this folder as the home directory for the analysis.




