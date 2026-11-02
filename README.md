# Medulloblastoma Machine Learning Analysis

Exploring Machine Learning Approaches for Gene Expression Data Analysis

## Overview

This repository focuses on applying fundamental machine learning techniques to gene expression data from medulloblastoma, a type of brain tumor.

The main objective is to explore how machine learning algorithms can be used to analyze high-dimensional biological datasets, identify patterns in gene expression, and investigate relationships between molecular features and disease status.

This is an educational and practical project developed to strengthen my skills in Python, machine learning, and computational biology.

## Dataset

The dataset used in this project is obtained from the NCBI Gene Expression Omnibus (GEO):

- **GEO Accession:** [GSE124814](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE124814)
- **Data Type:** Gene expression microarray
- **Research Area:** Medulloblastoma

### Previous Data Processing

Some of the data retrieval, preprocessing, quality control, gene annotation, and gene expression analysis steps were previously performed in a separate project:

**[Medulloblastoma-Microarray-Analysis](https://github.com/Sina-moradizadeh/Medulloblastoma-Microarray-Analysis)**

That repository focuses on microarray analysis, including differential gene expression analysis using `limma`, data visualization, and functional enrichment analysis.

The current repository builds upon this previous work, with a particular focus on exploring machine learning methods for biological data.

For more information about the dataset and its organization, see the [`data/README.md`](data/README.md) file.

## Repository Structure

```text
Medulloblastoma-ML-Analysis/
│
├── data/
│   ├── README.md
│   ├── processed/
│   └── metadata/
│
├── src/
│   ├── 01-Python-MachineLearning.ipynb
│   ├── 02-SimpleLinearRegression.ipynb
│   ├── 03-K-MeansClustering.ipynb
│   └── 04-SVM.ipynb
│
├── results/
│
└── README.md
```

## Notebooks and Analysis

### 01. Python and Machine Learning Fundamentals

Introduction to Python concepts and fundamental machine learning workflows.

### 02. Simple Linear Regression

Exploring linear relationships between variables and implementing a basic regression model using Python.

### 03. K-Means Clustering

Applying unsupervised learning to explore patterns and groupings within gene expression data.

### 04. Support Vector Machine (SVM)

Exploring Support Vector Machines as a supervised learning approach for classification tasks involving biological data.

## Tools and Technologies

| Category | Tools |
|---|---|
| Programming Language | Python |
| Environment | Jupyter Notebook |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Biological Data | Gene Expression Microarray |

## Learning Objectives

- Apply machine learning algorithms to biological datasets.
- Understand supervised and unsupervised learning approaches.
- Explore regression, clustering, and classification methods.
- Work with high-dimensional gene expression data.
- Develop practical skills in Python and computational biology.
- Understand the challenges of machine learning in biomedical research.

## Future Work

- Dimensionality reduction using PCA.
- Feature selection for high-dimensional gene expression data.
- Model evaluation and cross-validation.
- Comparison of different classification algorithms.
- Investigation of potential gene expression biomarkers.

## Related Project

**[Medulloblastoma-Microarray-Analysis](https://github.com/Sina-moradizadeh/Medulloblastoma-Microarray-Analysis)**

A complementary project focusing on microarray data preprocessing, differential gene expression analysis, and functional enrichment.

## Author

**Sina Moradizadeh**

M.Sc. Student in Genetics | Bioinformatics | Computational Biology

GitHub: [Sina-moradizadeh](https://github.com/Sina-moradizadeh)
