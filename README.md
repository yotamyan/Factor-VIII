# 🧬 Gene Interactions and Machinary  
### A Python tool to uncover gene networks behind cell-specific protein secretion

---

## 📌 Overview

A Python-based tool designed to help identify gene interaction networks that enable specific cells to produce target proteins — such as **Factor VIII**, which is missing in patients with **Hemophilia A**.

This tool was built to support biological research into cell reprogramming and gene therapy. It allows users to analyze gene expression datasets, isolate key regulatory genes, and visualize gene interaction networks in a tissue-specific manner.

> 🔧 No biology background is required to use this tool — just load a dataset and choose a target gene.

---

## 🎯 Project Goal

In my master's research, I am attempting to genetically engineer **blood-derived endothelial cells** to secrete **Factor VIII**. This tool helps identify what makes **liver endothelial cells** (which naturally produce this protein) different from others (e.g., heart cells), by analyzing the **gene networks ("machinery")** involved in the process.

---

## 🗂️ Features

- 📂 Load gene expression data (CSV or HDF5)
- 🔍 Filter for specific cell types (e.g., endothelial cells)
- 🧬 Analyze gene-gene co-expression with a target gene
- 🧠 Build and visualize interaction networks
- 📊 Compare gene networks across tissues

---

## 🛠️ Tech Stack

- `pandas` — data manipulation  
- `networkx` — gene network analysis  
- `matplotlib` / `plotly` — visualizations  
- `scikit-learn` — optional dimensionality reduction  
- (optional) `scanpy` — single-cell data integration  
- (optional) `streamlit` — interactive user interface

---
