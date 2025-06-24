# README

## Citation
Mobilio D., ..., Singh S. (2025) *in preparation.* 

## Scripts

The scripts used to generate figures/results in the current manuscript are provided in this repository. All data are publicly available or may be obtained from authors upon reasonable request.

- Brain metastasis scRNA-seq data consolition and preprocessing `BM_01_preprocessing.Rmd`
- DHODH and GSDME expression and function in brain metastases `BM_02_analysis.Rmd`

## Installation Guide

All analyses were run in R version 4.2.2 using the packages detailed in the “R Session Info” section below. Approximate install/set-up time is 20-30 minutes.

Instructions on how to install R (and RStudio) can be found here: [RStudio Installation Guide](https://rstudio-education.github.io/hopr/starting.html).

Instructions on how to install R packages can be found here: [R Packages Installation](https://rstudio-education.github.io/hopr/packages2.html).

## Instructions for Use

R script is provided as Rmarkdown files and are intended to be run in order chunk by chunk to ensure all variables have been appropriately defined for downstream analyses. In sections where data are loaded from local directories, users will have to specify the file location. 

## System Requirements

R version 4.2.2 (2022-10-31 ucrt)  
Platform: x86_64-w64-mingw32/x64 (64-bit)  
Running under: Windows 10 x64 (build 19045)  
