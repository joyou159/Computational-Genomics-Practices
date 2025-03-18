# Compgen Course 2025: Multi-omics Integration Using Deep Learning

This repository contains three homework assignments that I have completed as part of the Compgen Course 2025, Module 3: Multi-omics Integration Using Deep Learning. Each assignment focuses on different aspects of computational biology and bioinformatics.

## Assignments

### Homework 1: Modeling Breast Cancer Subtypes

**Description:**  
This task involves using a multi-omic dataset of Breast Cancer samples from the METABRIC consortium. The dataset includes gene expression, copy number alteration, mutation, and clinical metadata. The goal is to explore and analyze these features to classify breast cancer subtypes effectively.

### Homework 2: Finding Survival Markers in Lower Grade Glioma (LGG) and Glioblastoma Multiforme (GBM)

**Description:**  
This task involves analyzing a multi-omic dataset of brain cancer samples, including LGG and GBM. The objective is to identify survival markers by leveraging mutation and copy number alteration data alongside clinical information. The dataset is preprocessed and split into training and testing sets.

### Homework 3: Benchmarking Deep Learning Architectures on Multi-Omics Data

**Description:**  
This task focuses on benchmarking various deep learning models using multi-omic data from human cancer cell lines sourced from the CCLE (Cancer Cell Line Encyclopedia) and GDSC (Genomics of Drug Sensitivity in Cancer) databases. The objective is to predict drug responses for “Erlotinib” by building models on the CCLE dataset and evaluating their performance on the GDSC dataset.

The assignment involves testing different deep learning architectures, including at least two of the following: DirectPred, Supervised VAE, and GNN. Additionally, we will explore various combinations of omic data types, such as mutation, mutation + RNA, and mutation + CNV, testing at least two of these combinations. We will also compare different fusion methods, including early and intermediate fusion (note that GNNs only support early fusion).

The results of these experiments will be analyzed in a Jupyter notebook to determine the best-performing models and identify key predictive biomarkers associated with drug responses.

## Acknowledgments

I would like to extend my sincere gratitude to [Bora Uyar](https://scholar.google.de/citations?user=YEZr1LUAAAAJ&hl=en) from the Max Delbrueck Center for Molecular Medicine - The Berlin Institute for Medical Systems Biology for this amazing journey.