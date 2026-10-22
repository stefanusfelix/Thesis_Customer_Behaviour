# Customer Behaviour Discovery Using Temporal Clustering and Association Rule Mining

Code and data for the Master of Data Science minor thesis (FIT5128, Monash University)
by Stefanus Felix Wigna Sunarto, supervised by Dr. Jesmin Nahar.

## Contents
- `main.ipynb` – full analysis: data cleaning, EDA, RFM features, K-Means++
  clustering and archetype alignment, FP-Growth rule mining, Mann-Whitney tests,
  size-matched null model, and rule-persistence analysis.
- `Online Retail.xlsx` – UCI Online Retail dataset.

## How to reproduce
1. Install Python 3.12 and the packages in `requirements.txt`:
   `pip install -r requirements.txt`
2. Keep `Online Retail.xlsx` in the same folder as the notebook.
3. Open the notebook and run *Restart Kernel and Run All Cells*.

## Data
Chen, D. (2015). *Online Retail* [Dataset]. UCI Machine Learning Repository.
https://doi.org/10.24432/C5BW33. Licensed under CC BY 4.0.
