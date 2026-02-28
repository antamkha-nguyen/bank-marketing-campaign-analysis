# Bank Marketing Campaign Analysis

This project analyzes direct marketing campaign records from a Portuguese bank to identify patterns that drive term-deposit subscription, supporting future campaign targeting efficiency.

**Dataset:** [UCI Bank Marketing](https://archive.ics.uci.edu/dataset/222/bank+marketing) (45,211 records, 16 features)

## Key Findings

- Campaigns in March, September, October, and December yield the highest conversion rates
- Clients who subscribed in a previous campaign are the strongest retargeting segment
- Cellular contacts outperform telephone contacts
- High call frequency correlates negatively with subscription

## Models Trained

Logistic Regression, Decision Tree, Random Forest, KNN, LinearSVC, Neural Network  
Evaluated using stratified 5-fold CV with F1 score as the primary metric (class imbalance: around 88% non-subscribers).

## Setup

```bash
pip install -r requirements.txt
jupyter notebook bank-marketing-campaign-analysis.ipynb
```

No data download needed. The dataset is fetched automatically from the UCI ML Repository.

## Dashboard

Explore the interactive version on [Tableau Public]([https://public.tableau.com/your-dashboard-link](https://public.tableau.com/app/profile/an.tam.kha.nguyen.2002/viz/GSARealEstatePortfolioAnalysis/Dashboard3)).
