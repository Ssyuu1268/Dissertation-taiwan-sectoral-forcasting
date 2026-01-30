# PCA-LSTM with Economic Policy Uncertainty (EPU) for Taiwan Sector Indices

Master’s thesis submitted for the **MSc/MDS in Data Science (Durham University)** (Sep 2025).  
This study evaluates whether adding **Economic Policy Uncertainty (EPU)** indices (US/China/Taiwan) and the **US–China Tension Index** improves **LSTM** forecasting for **Taiwan’s sectoral stock indices** using a **PCA-LSTM** framework with **walk-forward validation**.

## Research Question
Can policy-uncertainty signals (US/China/TW EPU + US–China tension) improve sector-level forecasting performance beyond macro + technical baselines?

## Data & Scope
- Period: **2005–2021**
- Sectors: **Electronics, Finance, Transportation, Steel, Construction**
- Features: macroeconomic + technical indicators + policy uncertainty indices
- Method: **PCA for dimensionality reduction** + **LSTM**, evaluated via **walk-forward validation**

## Key Findings (high level)
- Adding EPU indices improves predictive performance, but **the magnitude differs by sector**.
- Policy uncertainty signals show **heterogeneous spillovers** across industries, consistent with sector-specific sensitivity to global uncertainty.

## Repository Contents
- `Z0207455-Research Project.pdf` — Full report (methods, experiments, results, discussion)
- `README.md` — Project overview

## How to View
GitHub typically renders PDFs directly in-browser. If the preview fails, click **Download** / **View raw** to open it locally.

## Citation
If you reference this work, please cite the thesis report in this repository.

## Disclaimer
This repository is for academic portfolio use.
