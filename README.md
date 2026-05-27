# Identifying a Novel Biomarker from the TCGA Dataset
## Bioinformatics Workflow
Glioblastoma (GBM) Novel Biomarker ARSI Identification and Analysis

This repository contains R Markdown files, scripts, and data used to investigate the impact of GBM ARSI (Arylsulfatase Family Member 1) on glioblastoma patient survival. The analysis includes survival modeling, visualization, and gene expression comparisons using TCGA dataset.

## Project Contents: 
- Final_MD.Rmd — Full R Markdown analysis (survival models, statistical tests, plots)
- RICKETTS_CI_Assignment_1 — HTML Knit output containing all code, outputs, and figures
- Folder "Presentation" — RICKETTS_CI_Presentation_Updated
- Folder "Figures" — all plots and figures

## Analysis Overview

### The analysis investigates:
- Cox proportional hazards models
- ARSI gene expression between GBM Subtypes (Classical, Mesenchymal, Neural, and Proneural)
- Age-related survival index (ARSI) in GBM patients
- Kaplan–Meier survival curves
- Associations between methylation and survival
- Associations between CNV and survival
- Protein expression correlation using the RPPA dataset

### Technologies Used: 
- R (tidyverse, survival, survminer, ggplot2)
- R Markdown
- ggplot2 for visualization
- Additional R packages for statistical modelling

### How to Run the Analysis: 
- Clone the repository: git clone https://github.com/USERNAME/REPOSITORY_NAME.git
- Open Final_MD.Rmd in RStudio.
- Install required R packages (listed at the top of the Rmd).
- Follow comments to download data through command lines. 
- Knit the R Markdown file to produce HTML or PDF output.

## License
This repository is published for viewing, reference, and personal interest only.

## Author
Chyi Ricketts
Imperial College London  
