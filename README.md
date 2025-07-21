# Comparative Analysis of Heart and Liver Endothelial Cells using scRNA-seq

This project analyzes single-cell RNA-sequencing (scRNA-seq) data from murine heart and liver tissues, with a focus on endothelial cells. The goal is to identify and compare endothelial subpopulations between these two organs, highlighting both shared and tissue-specific features.

## 🧪 Dataset & Scope

The analysis is based on previously annotated scRNA-seq datasets from the heart and liver. Only endothelial cells are retained for downstream comparison.

## 📊 Key Steps in the Analysis

1. **Data Loading and Filtering**
   - Load heart and liver AnnData objects
   - Subset to endothelial cells only

2. **Merging and Preprocessing**
   - Merge heart and liver datasets
   - Normalize and scale gene expression
   - Identify highly variable genes

3. **Dimensionality Reduction and Clustering**
   - Perform PCA and compute neighborhood graph
   - Run UMAP for visualization
   - Leiden clustering to identify endothelial subtypes

4. **Annotation and Marker Gene Analysis**
   - Assign cell type labels based on marker genes
   - Visualize gene expression across clusters

5. **Organ-Specific Comparison**
   - Compare endothelial cluster compositions between heart and liver
   - Identify differentially expressed genes
   - Visualize tissue-specific markers

6. **Enrichment Analysis**
   - Perform functional enrichment (e.g., GO, pathway analysis) on cluster-specific genes

## 📈 Outputs

- UMAP plots showing clustering and tissue distribution
- Dot plots and violin plots for marker gene expression
- Bar plots comparing cluster proportions across organs
