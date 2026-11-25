# 6BUIS017W CRM & CM with Business Intelligence — Individual Coursework

**Student Name:** Mohamed Dilshad  
**UOW ID:** w2121524  
**IIT No:** 20241148  
**Lecturer:** Mr. Fouzul Hassan  
**Repository:** https://github.com/mhddilshadgit/cwk1-sp500-rfm-segmentation

## Overview
Market analysis and stock segmentation of S&P 500 equity constituents against the `^GSPC` benchmark over the four-year study period (`2021-01-01` to `2025-01-01`, end date exclusive; `N = 488` valid shares across `208` aligned weekly observations). The coursework compares traditional risk-return segmentation (mean weekly return and weekly beta) with an adapted trading-activity RFM framework (Recency, Frequency, Monetary) using Ward hierarchical clustering and K-Means (`k = 3`), followed by correlation and Monetary-removal sensitivity checks.

## Repository Contents
- **`CRM_CW_Tasks_W2121524.ipynb`** — Complete, standalone, Google Colab-compatible Jupyter Notebook structured sequentially across Task 1 (1.1–1.5), Task 2 (2.1–2.5.2), and Task 3.
- **`6BUIS017W_CRM_CW_20241148_Dilshad.pdf`** — Final submission-ready academic coursework report (including cover page, table of contents, Gen AI declaration, Tasks 1–3, and Harvard references).
- **`requirements.txt`** — Python dependencies for local or Colab execution.

## Reproducibility
Run locally or upload `CRM_CW_Tasks_W2121524.ipynb` directly to Google Colab:

```bash
pip install -r requirements.txt
jupyter lab CRM_CW_Tasks_W2121524.ipynb
```
