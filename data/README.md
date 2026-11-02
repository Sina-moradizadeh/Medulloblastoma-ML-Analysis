# Data Description

## Dataset Source

The dataset used in this machine learning project is obtained from the **NCBI Gene Expression Omnibus (GEO)** database.

- **GEO Accession:** [GSE124814](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE124814)
- **Data Type:** Gene expression microarray data
- **Research Area:** Medulloblastoma
- **Platform:** Affymetrix microarray

## Data Description

GSE124814 contains gene expression profiles used to investigate medulloblastoma and related sample groups.

This dataset is used in the current project to explore machine learning approaches for distinguishing healthy and cancer samples based on gene expression patterns.

## Previous Data Processing

Part of the data retrieval, preprocessing, quality control, gene annotation, and gene expression analysis has already been performed in a separate repository:

**[Medulloblastoma-Microarray-Analysis](https://github.com/Sina-moradizadeh/Medulloblastoma-Microarray-Analysis)**

That repository focuses on microarray data analysis, including differential gene expression analysis using `limma`, data visualization, and functional enrichment analysis.

The current repository builds upon that previous work and focuses on the machine learning aspects of the dataset, including feature preparation, dimensionality reduction, model training, and performance evaluation.

## Data Availability and Reproducibility

The original dataset is publicly available through NCBI GEO.

To ensure reproducibility and avoid unnecessary duplication of large files, the original dataset is not necessarily stored directly in this repository. The analysis scripts document the data preparation and processing steps required to generate the input data for machine learning.


