# EK: A Stratified Lineage-Agnostic Analysis of PRP Expression and Erastin Resistance

This repository contains the data analysis, statistical modeling, and visualizations for the study:

**"A Stratified, Lineage-Agnostic Analysis of Persulfide-Related Protein Expression and Erastin Resistance Across Cancer Cell Lines"**  
by **Omer Ekmel Kara**

---

## Project Overview

This study investigates the relationship between persulfide-related protein (PRP) expression and erastin resistance in cancer cell lines, using a stratified, lineage-agnostic framework.

The analysis integrates:
- **DepMap gene expression** and **drug screening data** wich are saved as csv files named **ERASTIN (BRD_BRD-A25004090-001-08-4) log2 fold change** and **harmonized_MS_CCLE_Gygi** in order. Both can be found in the file called "depmapdata" 
- Protein annotation matching
- Statistical modeling and visualization in R
- More details about 
---

## 📁 Repository Contents

- `python/`:  
  Contains Python scripts for:
  - Parsing DepMap expression and drug screen data
  - Replacing Uniprot and DepMap IDs with protein names and cell line abbreviations
  - Merging expression and drug response datasets

- `R/`:  
  R scripts for:
  - Statistical tests and modeling
  - Generating all plots and visual summaries for the manuscript

- `manuscript/`:  
  - `A Stratified, Lineage-Agnostic Analysis of Persulfide-Related Protein Expression and Erastin Resistance Across Cancer Cell Lines.pdf` and `A Stratified, Lineage-Agnostic Analysis of Persulfide-Related Protein Expression and Erastin Resistance Across Cancer Cell Lines.docx`: Final versions of the article

---

### Used Libraries
- R (tested with R 4.4.3)
   -'tidyverse'
   -'ggplot2'
   -'Seurat'
   -'broom'
   - 'car'
- Python (tested with Python 3.12)
   - `pandas`
   - `numpy`
---
### This project is shared under the MIT License contact me
