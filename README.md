# Customer Retention Analysis and RFM Segmentation in E-commerce  

## Project Overview  
Data-driven analysis of customer retention in an electronics e-commerce dataset (2.6M transactions, Apr–Nov 2020).  
The project applies cohort-based retention analysis, RFM analytics, and customer segmentation techniques to uncover behavioral patterns and generate actionable business insights.  

---

## Objectives  
- Measure customer retention trends over time using cohort analysis.  
- Apply **RFM (Recency, Frequency, Monetary) analysis** to identify key customer groups.  
- Perform **segmentation** using machine learning (clustering) to discover behavioral patterns.  
- Translate findings into **business-focused insights** for retention and revenue growth strategies.  

---

## Dataset  
- **Source:** [Kaggle – E-commerce Purchase History from Electronics Store](https://www.kaggle.com/datasets/mkechinov/ecommerce-purchase-history-from-electronics-store/data)  
- **Provider:** [REES46 Marketing Platform](https://rees46.com/)  
- **Size:** ~2.6M purchase events  
- **Timeline:** April 2020 – November 2020  
- **Features:**  
  - `event_time` – purchase timestamp  
  - `order_id` – unique order identifier  
  - `user_id` – customer identifier  
  - `product_id` – product identifier  
  - `category_id` – category identifier  
  - `category_code` – category label (nullable)  
  - `brand` – brand name (nullable)  
  - `price` – product price  

---

## Tools & Technologies  
- **Language:** Python  
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn, plotly  
- **Optional:** lifelines (for retention curves), mlxtend (for association rules)  
- **Dashboard:** Streamlit  

---

## Key Analyses  
1. **Customer Retention Analysis**  
   - Cohort retention tables & heatmaps  
   - Survival/retention curves  

2. **RFM Analytics**  
   - Recency, Frequency, Monetary scoring  
   - Segment profiles and revenue contribution  

3. **Segmentation (Machine Learning)**  
   - Feature engineering from RFM + behavioral metrics  
   - K-Means clustering & cluster profiling  
   - Business insights and recommended actions  

---

## Results (to be updated)  
- Key insights will be summarized here once analysis is complete.  
- Visualizations and cluster profiles will be added.  

---

## Dashboard (to be added)  
An interactive Streamlit dashboard will be developed for exploring cohorts, RFM segments, and clusters.  

---

## References  
- Dataset: [Kaggle – E-commerce Purchase History from Electronics Store](https://www.kaggle.com/datasets/mkechinov/ecommerce-purchase-history-from-electronics-store/data)  
- Provider: [REES46 Marketing Platform](https://rees46.com/) 