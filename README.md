# Customer Churn Analysis

Exploratory data analysis on a telecom dataset of 7,000+ customers to uncover why customers churn and what predicts it.

## Key Findings
- Month-to-month contract customers churn at ~43% vs ~3% for two-year contracts
- 50%+ of churn happens in the first 12 months of tenure
- High monthly charges (>$70) correlate strongly with churn

## Tech Stack
Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook

## Dataset
[Telco Customer Churn — Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## How to Run
```bash
git clone https://github.com/piyushjuneja21/churn-analysis
cd churn-analysis
python3 -m venv venv && source venv/bin/activate
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook
```
Open `notebooks/churn_analysis.ipynb` and run all cells.
