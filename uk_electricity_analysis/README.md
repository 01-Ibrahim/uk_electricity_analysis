# UK Electricity Bill Analysis

## Overview
This project analyzes **domestic electricity bills in the UK (2022)** using official UK government statistics.  
The goal is to explore regional differences, compare payment methods, and visualize trends in electricity bills.

## Dataset
- Source: [UK Government Energy Statistics](https://www.gov.uk/government/statistics/annual-domestic-energy-bills)
- Cleaned and preprocessed for analysis.
- Stored as `data/cleaned_data.csv`.

## Project Structure

uk_electricity_analysis/
├── data/ # Cleaned dataset
├── notebooks/ # Jupyter notebook with code
├── outputs/figures/ # Charts and visualizations
├── README.md # Project description
├── requirements.txt # Python dependencies
└── LICENSE # MIT License

## Analysis Steps
1. **Data Cleaning** – Removed metadata rows, fixed column names, and ensured numeric types.  
2. **Exploratory Analysis** – Calculated average, min, and max electricity bills by region.  
3. **Visualization** –  
   - Overall bill by region  
   - Average bill by payment method (Credit, Direct Debit, Prepayment)  
4. **Additional Insights** – Top 5 regions with highest electricity bills.

## Dependencies
- Python 3.12+
- pandas
- matplotlib

Install dependencies:

```bash
pip install -r requirements.txt

How to Use
1. Clone the repository:
git clone https://github.com/01-Ibrahim/uk_electricity_analysis.git
2. Open the notebook in notebooks/uk_electricity_analysis.ipynb and run all cells.
3. Explore outputs/figures/ for generated charts.
4. Check data/cleaned_data.csv if you want to reuse the dataset.

**Author**
**Mohammed Ibrahim**
https://www.linkedin.com/in/mohd-ibrahim17/
https://github.com/01-Ibrahim


License
MIT License