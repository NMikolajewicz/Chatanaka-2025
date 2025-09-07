# Chatanaka-2025

# README

## Citation
Chatanaka, M. K., Avery, L. M., Mikolajewicz, N., Ajisebutu, A., de Macedo Filho, L., Wang, M., Brown, J., Cohen, R., Gorham, T., Misaghian, S., Padmanabhan, N., Romero, D., Stengelin, M., Mathew, A., Sigal, G., Wohlstadter, J., Horbinski, C., McCortney, K., Zadeh, G., Mansouri, A., & Diamandis, E. P. (2025). A seven-plasma biomarker panel (GFAP, FABP4, MMP1, MMP3, MMP9, NfL, T-Tau) for classification of benign and malignant brain tumors. *in preparation*. 

## Scripts

The script used to generate figures/results in the current manuscript is provided in this repository. The appropriate single-cell (Seurat) object must be provided as input as specified in the script itself and/or manuscript. All data are publicly available or may be obtained from authors upon reasonable request.

- Dimensional reduction/visualization and classificaiton modeling: `Plasma_Biomarker_Analysis_060925.Rmd`

## Installation Guide

All analyses were run in R version 4.2.2 using the packages detailed in the “R Session Info” section below. Approximate install/set-up time is 20-30 minutes.

Instructions on how to install R (and RStudio) can be found here: [RStudio Installation Guide](https://rstudio-education.github.io/hopr/starting.html).

Instructions on how to install R packages can be found here: [R Packages Installation](https://rstudio-education.github.io/hopr/packages2.html).

## Instructions for Use

R script is provided as Rmarkdown files and are intended to be run in order chunk by chunk to ensure all variables have been appropriately defined for downstream analyses. In sections where data are loaded from local directories, users will have to specify the file location. Following these steps, the key scRNA-seq figures that are presented in the manuscript can be reproduced with the provided scripts.

## System Requirements

R version 4.2.2 (2022-10-31 ucrt)  
Platform: x86_64-w64-mingw32/x64 (64-bit)  
Running under: Windows 10 x64 (build 19045)  


## Package Information

| Package       | Version | Package        | Version        |
| ------------- | ------- | -------------- | -------------- |
| ModelMetrics  | 1.2.2.2 | broom          | 1.0.1          |
| klaR          | 1.7-1   | MASS           | 7.3-58.1       |
| nnet          | 7.3-18  | kernlab        | 0.9-31         |
| glmnet        | 4.1-6   | Matrix         | 1.5-4.1        |
| mice          | 3.18.0  | VIM            | 6.2.2          |
| colorspace    | 2.0-3   | limma          | 3.54.0         |
| sva           | 3.46.0  | BiocParallel   | 1.32.1         |
| genefilter    | 1.80.0  | mgcv           | 1.8-41         |
| nlme          | 3.1-160 | corrplot       | 0.92           |
| ROCR          | 1.0-11  | pROC           | 1.18.0         |
| e1071         | 1.7-12  | xgboost        | 1.7.11.1       |
| randomForest  | 4.7-1.1 | caret          | 6.0-93         |
| lattice       | 0.20-45 | forcats        | 0.5.2          |
| purrr         | 1.0.4   | readr          | 2.1.3          |
| tibble        | 3.2.1   | tidyverse      | 1.3.2          |
| scMiko        | 0.1.0   | doParallel     | 1.0.17         |
| iterators     | 1.0.14  | foreach        | 1.5.2          |
| future        | 1.29.0  | tm             | 0.7-9          |
| NLP           | 0.2-1   | stringr        | 1.4.1          |
| quantreg      | 5.94    | ddpcr          | 1.15           |
| survminer     | 0.4.9   | ggpubr         | 0.4.0          |
| survival      | 3.4-0   | flexdashboard  | 0.6.0          |
| DT            | 0.26    | plotly         | 4.10.1         |
| RColorBrewer  | 1.1-3   | ggrepel        | 0.9.2          |
| ggExtra       | 0.10.0  | ggpmisc        | 0.5.1          |
| ggpp          | 0.4.5   | gridExtra      | 2.3            |
| ggplot2       | 3.4.4   | topGO          | 2.50.0         |
| SparseM       | 1.81    | GO.db          | 3.16.0         |
| graph         | 1.76.0  | homologene     | 1.4.68.19.3.27 |
| org.Hs.eg.db  | 3.16.0  | org.Mm.eg.db   | 3.16.0         |
| AnnotationDbi | 1.60.0  | IRanges        | 2.32.0         |
| S4Vectors     | 0.36.0  | Biobase        | 2.58.0         |
| BiocGenerics  | 0.44.0  | preprocessCore | 1.60.0         |
| GSVA          | 1.46.0  | SeuratObject   | 4.1.3          |
| Seurat        | 4.2.1   | reshape2       | 1.4.4          |
| tidyr         | 1.2.1   | dplyr          | 1.1.4          |
| plyr          | 1.8.7   | —              | —              |

