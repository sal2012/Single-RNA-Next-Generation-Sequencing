# Single-Cell RNA Sequencing Analysis

This repository is dedicated to educational materials and practical tutorials focused on Single-Cell RNA Sequencing (scRNA-seq). It provides comprehensive resources to understand and apply scRNA-seq to uncover cellular complexity and heterogeneity.

## Contents

- **Single-Cell RNA Sequencing.pptx**: A PowerPoint presentation that introduces the fundamentals of scRNA-seq, including detailed workflows and key applications.
- **Tutorial_rmarkdown1.Rmd**: An R Markdown tutorial that demonstrates the analysis of scRNA-seq data using the Seurat package, from data preprocessing to visualization.

## Getting Started

To make the most out of the resources in this repository, follow these steps:

### Prerequisites

Ensure you have the following installed:
- R and RStudio
- Seurat package for scRNA-seq analysis

To install Seurat, run the following in R:
```r
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("Seurat")

## Using the PowerPoint Presentation

1. Download and open `Single-Cell RNA Sequencing.pptx` to review the theoretical background and detailed workflows of scRNA-seq.
2. Follow the step-by-step guide through the processes of sample preparation, sequencing, and data analysis.

## Using the R Markdown Tutorial

1. Download `Tutorial_rmarkdown1.Rmd`.
2. Open the file in RStudio.
3. Execute the code chunks sequentially to perform scRNA-seq data analysis. This includes data normalization, variable feature selection, clustering, and data visualization using PCA and UMAP.


## Contact

For further information, contact:
- **Salwa Elsaadawy**
- Email: [sme76@georgetown.edu]
