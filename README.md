# amazon-india-product-analytics
# Amazon India Product Analytics & Sentiment Analysis

## Overview
This project analyzes 1,400+ Amazon India products to understand how pricing, discounts, and customer reviews influence product ratings.

The goal was to evaluate whether commonly assumed drivers of customer satisfaction (discounts and sentiment) actually align with product ratings.

## Key Insights
* Weak correlation between review sentiment and ratings (**r ≈ 0.18**)
* Discount percentage does not strongly influence product ratings
* Identified **“discount traps”** — products with high discounts but low ratings
* Customer satisfaction is influenced by factors beyond pricing and written reviews
  
## Techniques Used
* **Python**: Data cleaning, feature engineering, EDA
* **Pandas & Seaborn**: Data analysis and visualization
* **NLP (TextBlob)**: Sentiment analysis on customer reviews
* **Machine Learning**: Logistic Regression (~53% balanced accuracy)
* **Tableau**: Interactive dashboards for insights

## Dashboards

### 1. Overview Dashboard
* Sentiment vs Rating
* Discount vs Rating
* Category Comparison
* Value Score (Rating × Discount)

### 2. Discount Trap Analysis

* Highlighted products with **high discount (>50%) and low rating (<3.5)**

**Tableau Public Dashboard**:
[https://public.tableau.com/app/profile/nandini.arora2557/viz/AmazonIndiaProductAnalyticsSentimentAnalysis/AmazonIndiaProductAnalyticsPricingRatingsSentimentInsights]

##  Project Structure
```
amazon-product-analytics/
│
├── notebook.ipynb
├── amazon_final.csv
├── dashboard_overview.png
├── discount_traps.png
└── README.md
```

## Key Takeaway
Traditional product metrics like price, discount, and even review sentiment are weak predictors of customer satisfaction on Amazon India. This suggests that user ratings are influenced by additional factors not captured in structured data.


## Future Improvements
* Incorporate advanced NLP models (BERT-based sentiment analysis)
* Include additional features such as brand, delivery time, and product type
* Improve predictive modeling using more advanced ML techniques

##  Contact
If you have feedback or suggestions, feel free to connect or reach out!
