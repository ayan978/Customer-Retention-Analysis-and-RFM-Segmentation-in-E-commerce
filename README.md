# Customer Retention and RFM Analytics in E-commerce

## Overview
This project analyzes customer purchasing behavior in an e-commerce setting to understand retention patterns, revenue concentration, and customer value. Using a combination of cohort analysis, RFM segmentation, and machine learning–based clustering, the project translates raw transaction data into actionable customer personas and business insights.

The focus is on practical, decision-oriented analytics rather than purely technical modeling.

---

## Business Objectives
1. Analyze customer retention behavior over time using cohort analysis  
2. Identify high-value customers and revenue concentration patterns  
3. Segment customers into actionable groups to support targeted retention and marketing strategies  

---

## Dataset
- **Source:** Kaggle – E-commerce Purchase History (Electronics Store, REES46)  
- **Scale:** ~2.6M transaction events  
- **Time period:** 2020  
- **Granularity:** Event-level data aggregated into order-level and user-level views  

---

## Methodology

### Data Preparation
- Explicit schema definition to prevent identifier precision loss
- Timestamp validation and filtering
- Order-level aggregation from event-level data
- Outlier handling using winsorization for robust revenue analysis

### Exploratory & Descriptive Analysis
- Revenue and basket-size distributions
- Monthly order and revenue trends
- Category and brand-level revenue concentration
- Revenue concentration across users

### Retention Analysis
- Monthly cohort construction based on first purchase date
- Cohort retention tables and heatmaps to quantify repeat behavior

### RFM Segmentation
- Recency, Frequency, and Monetary scoring using quantile-based bins
- Business-friendly RFM segments with clear behavioral interpretation
- Segment-level KPIs and recommended actions

### Machine Learning–Based Segmentation
- Feature engineering beyond RFM (basket size, purchase gaps, diversity, tenure)
- MiniBatch K-Means clustering with metric-based model selection
- Customer personas derived from cluster profiles
- Comparison of ML-based segmentation with traditional RFM segmentation

---

## Key Insights
- Customer retention drops sharply after the first purchase, with only a small core of repeat buyers persisting over time.
- Revenue is highly concentrated: a small fraction of users accounts for a large share of total sales.
- RFM segmentation provides a strong baseline understanding of customer value.
- ML-based segmentation adds behavioral depth, revealing distinct customer personas with different revenue and engagement profiles.

---

## Business Outcomes
- Identification of high-value customers requiring retention-first strategies
- Clear distinction between large low-value segments and small high-impact segments
- Actionable customer personas suitable for CRM targeting and campaign design

---

## Limitations
- Segmentation is based on historical behavior and does not guarantee future outcomes.
- Unsupervised clustering infers patterns without predefined business labels.
- Results depend on the chosen time window and available transaction history.

---

## Files
- `notebooks/` – Full analysis notebook  
- `outputs/` – Rendered PDF report  
- `data/` – Dataset (or instructions to obtain it)

---

## Tools & Technologies
- Python (pandas, NumPy, matplotlib, seaborn)
- scikit-learn
- Jupyter Notebook

---