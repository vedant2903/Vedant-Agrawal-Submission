# Vedant-Agrawal-Submission
# Order Flow Imbalance Feature Engineering

This repository contains the implementation of various Order Flow Imbalance (OFI) features as part of the research task based on the paper:

**"Cross-Impact of Order Flow Imbalance in Equity Markets"**  
*By Rama Cont, Mihai Cucuringu, and Chao Zhang (Quantitative Finance, 2023)*

---

##  Contents

- `ofi_features.py` — Core Python module for calculating OFI features
- `utils.py` — Utility functions for processing and reshaping order book data
- `notebooks/OFI_Demo.ipynb` — Example notebook showcasing feature construction
- `data/first_25000_rows.csv` — Sample order book data (not included here)
- `ofi_conceptual_answers.pdf` — Written conceptual answers (LaTeX-generated)
- `README.md` — This file

---

## Task Objectives

1. Construct the following OFI features:
   - **Best-Level OFI**
   - **Multi-Level OFI**
   - **Integrated OFI** (via PCA)
   - **Cross-Asset OFI** (with LASSO regression)

2. Provide theoretical responses to:
   - Why multi-level OFI is beneficial
   - Why Lasso is chosen over OLS
   - Why OFI is a better short-term return predictor than volume

---

## Setup Instructions

1. **Clone this repo**  
   ```bash
   git clone https://github.com/yourusername/ofi-feature-engineering.git
   cd ofi-feature-engineering
