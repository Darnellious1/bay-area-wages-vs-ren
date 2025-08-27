# Bay Area Wages vs Rent (2015=100)

[![Open In Colab](https://colab.research.googleusercontent.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Darnellious1/bay-area-wages-vs-rent/blob/main/analysis_portfolio.ipynb)

**Summary**  
Reproducible analysis of San Francisco–Oakland–Hayward wages vs. rent CPI, indexed to 2015=100. The project aligns QCEW wages with local CPI series, builds real wages and a wage-to-rent index, and produces clear figures plus a one-page brief.

**One-page brief:** [artifacts/brief.pdf](artifacts/brief.pdf)

## Figures
![Wages vs Rent (2015=100)](figures/sf_wage_vs_rent_clean.png)
![Real Wages vs Rent (2015=100)](figures/sf_real_wage_vs_rent_clean.png)

## Data & Notebook
- Dataset: [data/sf_quarterly_wage_rent.csv](data/sf_quarterly_wage_rent.csv)  
- Notebook: [analysis_portfolio.ipynb](analysis_portfolio.ipynb)

## Methods (short)
- **Wages:** BLS QCEW (FRED `ENUC418640510SA`)  
- **Prices:** CPI-U All Items (FRED `CUUSA422SA0`) and Rent of Primary Residence (FRED `CUUSA422SEHA`)  
- Monthly CPI averaged to **quarters**; both series indexed to
