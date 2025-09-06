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

