# Biomarker-Analysis
Biomarker Statistical analysis @KIST


## Task1 - Age vs Immune Cell Analysis

This task evaluates the association between **age** and **immune-cell features**.  
Both **feature-level** and **PC1-based block-level** analyses were performed with covariate adjustment.

- Partial correlation with age
- PC1 vs age analysis
- Separate analysis in **KUMC** and **AMC**
- FDR correction using **Benjamini–Hochberg**
  
<img width="191" height="148" alt="image" src="https://github.com/user-attachments/assets/8fea50f3-7f71-4425-9002-acb8bac9fd9b" />


---

## Task2 - Immune Cell vs Clinical Group Analysis

This task evaluates the association between **immune-cell groups** and **clinical biomarker groups**.  
Each group was summarized by **PC1**, and associations between groups were tested using partial Spearman correlation.

- PCA-based group summarization
- Immune group PC1 vs clinical group PC1
- Covariate-adjusted partial correlation
- Separate analysis in **KUMC** and **AMC**
- FDR correction using **Benjamini–Hochberg**


<img width="663" height="224" alt="image" src="https://github.com/user-attachments/assets/3868277e-4ee6-4452-bfac-62d59cb04ded" />
