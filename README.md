# User Retention Analysis — Subscription Business

## Project Overview
SQL and Python analysis on 7,032 subscription users to identify 
retention patterns and high-risk segments.

**Tools:** Python, pandas, matplotlib, seaborn, SQLite  
**Dataset:** IBM Telco Customer Churn (Kaggle)

## Key Findings
| Finding | Insight |
|---------|---------|
| Highest risk segment | New month-to-month users retain at only 48.6% |
| Tenure impact | First-year churn (47.7%) is 5× higher than 49+ months (9.5%) |
| Service type | Fiber optic churn (41.9%) is 2× higher than DSL (19.0%) |
| Best retention | Two-year contract users retain at 97-100% across all tenures |

## Business Recommendations
1. **12-month onboarding program** — structured check-ins at months 
   1, 3, 6, and 12 for all new users
2. **Contract upgrade incentives** — discounted first-year rate to 
   move month-to-month users to annual plans
3. **Fiber optic loyalty program** — dedicated retention program for 
   highest-paying users

## Files
- `analysis.ipynb` — full SQL + Python analysis notebook
- `data/telco-churn.csv` — dataset
- `charts/` — exported visualizations

## How to Run
```bash
pip install pandas matplotlib seaborn
jupyter notebook analysis.ipynb
```