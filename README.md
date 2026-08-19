# Netflix Customer Churn Analysis

Analysis of a 5,000 customer dataset to identify who churns, why, and how much revenue is at risk — using Python, SQL, and Tableau.

## What I did
- Cleaned and explored the dataset in Python (pandas)
- Loaded the data into SQLite and wrote SQL queries to answer business questions
- Segmented churn by subscription type, region, favorite genre, and login recency
- Calculated revenue at risk from churned customers
- Built an interactive Tableau dashboard to visualize the findings

## Key Findings
- **Overall churn rate: 50.3%** — half of all customers have churned
- **Login inactivity is the strongest churn signal**: customers inactive for 30+ days churn at 75.1%, vs. just 13.4% for those active in the     last week
- **Basic-tier subscribers churn the most** (61.8%) compared to Premium (43.7%)
- **Revenue at risk: $33,009.85/month (48.2% of total monthly revenue)**
- Region and genre had little effect on churn — engagement and plan tier matter far more than demographics

## Tools
Python (pandas), SQL (SQLite), Tableau

## Files
- `netflixproject.ipynb` — full analysis notebook
- `netflix_customer_churn.csv` — raw dataset
- `netflixchurned dashboard.twb` — Tableau dashboard file
