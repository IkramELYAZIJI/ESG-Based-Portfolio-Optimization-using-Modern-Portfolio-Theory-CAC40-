# ESG-Based-Portfolio-Optimization-using-Modern-Portfolio-Theory-CAC40-
Research project exploring ESG inclusion in Modern Portfolio Theory, analysing its effects on diversification, Sharpe ratios, and overall portfolio efficiency using CAC40 data

## 📘 Overview
This project explores how Environmental, Social, and Governance (ESG) criteria can be incorporated into Modern Portfolio Theory (MPT) when constructing and optimising portfolios.  
Using data from CAC40 companies, the study compares traditional portfolios with ESG-screened portfolios in terms of performance, risk, Sharpe ratio, and diversification.

## 🎯 Objectives
- Assess the impact of ESG criteria on portfolio construction.
- Compare risk–return characteristics of ESG vs. non-ESG portfolios.
- Implement mean-variance optimisation (Markowitz Model).
- Analyse changes in asset allocation after applying ESG criteria.

## 📂 Repository Structure
project/
│
├── data/ # Cleaned datasets
├── notebooks/ # Jupyter notebooks
└── README.md

## 📊 Data
- **Universe:** CAC40 historical daily prices for a period of 10 years.  
- **ESG data:** ratings from Sustainalytics.  
- **Risk-free rate:** Refinitv

## 🧠 Methodology
The analysis is structured into three main parts:
1. **Mean-Variance Portfolio Optimization of the CAC40**  
   - We begin with a focused analysis of the CAC40 portfolio using the classical Mean-Variance (MV) framework.  
   - The goal is to understand baseline portfolio performance and asset allocation without ESG constraints.

2. **Incorporation of ESG Criteria**  
   - We extend the MV optimization by integrating ESG criteria inspired by Pedersen et al. (2020).  
   - The model balances risk-return trade-offs while accounting for ESG scores, using metrics such as the Sharpe Ratio adjusted for ESG risk ratings.  
   - This step highlights how ESG considerations influence portfolio composition and performance.

3. **Robustness Check on a Different Sample**  
   - To avoid biases, particularly those arising from the COVID-19 pandemic, the same models are re-run on an alternative sample period.  
   - This ensures the observed effects of ESG integration are consistent and not driven by exceptional market conditions.

## 🛠️ Tools & Libraries
- Python (Jupyter Notebook)
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- PyPortfolioOpt
