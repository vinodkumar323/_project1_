# _project1_
# Customer Churn Analysis - Telecom Industry

**Presented by:** Thota Vinod Kumar

->Project Objective:

To predict telecom customer churn and provide actionable insights to retain users in a highly competitive telecom environment.


->Tools & Technologies:

- Python (Scikit-learn, ELI5)
- SQLite (for data storage)
- Pandas, NumPy
- Seaborn, Matplotlib
- Jupyter Notebook / VS Code


->Project Features:

- Data Preprocessing
- Binary Classification (Churn Prediction)
- Model Explainability with ELI5
- Customer Segmentation:
  - At Risk
  - Loyal
  - Dormant

-> SQL-Based Analysis:

- Aggregated call duration and complaint history
- Analyzed recharge frequency patterns
- Identified churn patterns using SQL queries
- Segmented high-risk users with behavior flags

-> Machine Learning Model:

- **Model Used:** Random Forest Classifier
- **Target Variable:** churn (Yes/No)
- **Training Features:** Tenure, usage, complaints, recharge patterns, etc.
- **Interpretability:** Used ELI5 for model explanation
- **Evaluation Metrics:** Accuracy Score, Confusion Matri

->Customer Segmentation"

- **At Risk:** High complaints, low recharge frequency
- **Loyal:** Long tenure, consistent activity, low churn probability
- **Dormant:** Low engagement, low complaints, moderate churn risk

->Final Recommendations:

- Focus on retaining high-value At-Risk customers
- Offer loyalty rewards to long-term users
- Launch re-engagement campaigns for Dormant customers
- Monitor recharge and complaint frequency closely




# Sentiment Analysis Visualization in Tableau

This project focuses on visualizing sentiment analysis of trending YouTube video titles using Tableau. The visualizations help to understand how people feel about trending videos by categorizing sentiments into **Positive**, **Negative**, and **Neutral**.

## Overview

Sentiment analysis is applied to video titles to classify the mood or emotion expressed. These sentiments are then visualized through various Tableau charts to answer key questions about the overall sentiment landscape of trending content.

---

## Included Visualizations

### 1. Bar Chart – Count of Sentiment Types  
**Purpose:** Shows the number of videos in each sentiment category (Positive, Negative, Neutral).  
- **Dimensions:** `title_sentiment`  
- **Measures:** Count of `video_id` (or unique identifier)  
- **Insights:** Understand the overall mood of trending videos.  
- **Color Coding:** Optional use of colors to differentiate sentiments (e.g., Green = Positive, Red = Negative).

---

### 2. Pie Chart – Sentiment Distribution  
**Purpose:** Visualizes sentiment proportions as parts of a whole.  
- **Dimensions:** `title_sentiment` (used as pie slices)  
- **Measures:** Count of `video_id` (used for slice size)  
- **Insights:** Percentage breakdown of Positive, Negative, and Neutral sentiments among trending videos.

---

### 3. Stacked Bar Chart – Sentiment by Category  
**Purpose:** Compares sentiment distribution across different video categories (e.g., Music, Gaming, News).  
- **Dimensions:** `category` (X-axis), `title_sentiment` (Color)  
- **Measures:** Count of `video_id` (Y-axis)  
- **Insights:** Identifies which categories have more positive or negative sentiments.

---

### 4. Stacked Bar Chart – Sentiment by Country (Region-wise Comparison)  
**Purpose:** Shows how sentiments vary across different countries or regions.  
- **Dimensions:** `country` (X-axis), `title_sentiment` (Color)  
- **Measures:** Count of `video_id` (Y-axis)  
- **Insights:** Compare regional differences in sentiment among trending videos.

---

### 5. Line Chart – Sentiment Trend Over Time (Optional)  
**Purpose:** Tracks sentiment changes over time to observe trends.  
- **Dimensions:** `trending_date` (X-axis), `title_sentiment` (Color)  
- **Measures:** Count of `video_id` (Y-axis)  
- **Insights:** Analyze how public sentiment evolves across days or months.

## How to Use

1. Load your dataset containing `video_id`, `title_sentiment`, `category`, `country`, and `trending_date` into Tableau.
2. Follow the instructions above to create each chart.
3. Use filters or parameters in Tableau to explore sentiments by different dimensions (e.g., by category or country).
4. Optionally, build a dashboard combining these charts for an interactive sentiment analysis report.

---

