## 🧬 Bioinformatic Approaches to Regulatory Genomics & Epigenomics

**ETH Zürich — Spring Semester 2026**  
Instructor: P.-L. Germain

---

## 📖 Overview

This repository contains my assignments and practical work for the ETH Zürich course Bioinformatic Approaches to Regulatory Genomics and Epigenomics.

The course focuses on genome-wide analysis of chromatin and regulatory data, with hands-on exploration using R and the Bioconductor ecosystem. The goal is to develop both conceptual understanding of regulatory genomics and practical skills for analyzing NGS-based chromatin datasets.

---

## 🎯 Learning Objectives

The assignments in this repository aim to:

- Working with the Bioconductor ecosystem
- Handling genomic data structures (e.g., GRanges, EnsDb, TxDb)
- Exploring and visualizing epigenomic datasets
- ATAC-seq and ChIP-seq analysis workflows
- Motif analysis and regulatory element interpretation
- Understanding chromatin regulation and transcriptional control

---

## 📂 Repository Structure

Each assignment folder follows this structure:

```
assignment_X/
│
├── assignment_X.Rmd        # R Markdown source file
├── assignment_X.html       # Rendered HTML report
└── data/                   # Input files (if required/permitted)
```
---

## 🔬 Reproducibility

All reports are generated using R Markdown.

To reproduce an assignment:

```r
rmarkdown::render("assignment_X.Rmd")
