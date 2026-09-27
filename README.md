# Cardiomyocyte Maturation scRNA-seq Analysis

This project analyzes published neonatal mouse heart scRNA-seq and snRNA-seq data 
to investigate changes in cardiomyocytes (CMs) during maturation from day 2 to day 11 
of neonatal life, focusing on **transcriptional changes** and **intercellular communication**
between CMs and other cardiac cell types.

The analysis workflow is implemented in **RStudio** using **Seurat**, **clusterProfiler**,
**ReactomePA**, and **CellChat**.

<p align="center">
  <img src="Report/Workflow.png" width="800">
</p>

<p align="center">
  The data analysis pipeline and libraries used in this study.
</p>

### Data

The data were obtained from the **Sham control group** of neonatal mice. Mice underwent
Sham surgery at **postnatal day 1 (P1)** or **postnatal day 8 (P8)**, and ventricular
cells were collected at **1 and 3 days after surgery**.

Both **scRNA-seq** of non-cardiomyocytes and **snRNA-seq** of cardiomyocytes were
performed. This analysis included four neonatal timepoints from the Sham group:

| Timepoint | Experimental condition |
|---|---|
| **D2** | P1 + 1 day after Sham surgery |
| **D4** | P1 + 3 days after Sham surgery |
| **D9** | P8 + 1 day after Sham surgery |
| **D11** | P8 + 3 days after Sham surgery |

The dataset is publicly available through the
[**NCBI Gene Expression Omnibus (GEO)**](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE153480).

### Project Report

The complete project report is available
[**here**](Report/Diep_Thai_REPORT_F1_MOLEBIO.pdf).