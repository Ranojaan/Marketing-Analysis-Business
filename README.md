# 📊 Marketing Analysis for Innova

## 🧩 Project Overview

This project analyzes the effectiveness of marketing campaigns for **Innova**, an online retail company experiencing reduced customer engagement and conversion rates. Using real-world business data, this end-to-end analysis includes:

- Data extraction and cleaning using SQL
- Customer sentiment analysis using Python (VADER from NLTK)
- Business intelligence dashboard built in Power BI

The objective is to uncover marketing optimization opportunities and drive data-informed decisions.

---

## 🧠 Business Problem

Innova's marketing team reported the following issues:

- 📉 **Customer Engagement Decline**: Fewer users are interacting with the website and content.
- 🛒 **Conversion Rate Drop**: More traffic is arriving, but fewer purchases are being completed.
- 💰 **High Campaign Costs**: Marketing expenses have grown without proportional returns.
- 🗣️ **Need for Feedback Analysis**: Customer sentiment is not well understood.

---

## 🧪 Project Pipeline

### 1. 🔍 Data Extraction & Cleaning — SQL
- Connected to company marketing databases.
- Performed data joins, CTEs, filtering, and transformations.
- Cleaned data across multiple tables including campaigns, customers, and transactions.

### 2. 💬 Sentiment Analysis — Python (NLP)
- Analyzed customer reviews and social media comments to gauge sentiment.
- Used **VADER** sentiment analysis via NLTK to classify text into:
  - Positive
  - Neutral
  - Negative
- Aggregated scores by product and campaign for actionable feedback insights.

**Python Libraries Used**:
- `pandas` – for data manipulation and analysis
- `pyodbc` – for SQL database connection
- `sqlalchemy` – for SQL-based querying and ORM
- `nltk` – for natural language processing
  - `nltk.sentiment.vader` – sentiment scoring engine
  - `SentimentIntensityAnalyzer` – to compute sentiment polarity

### 3. 📊 Data Visualization — Power BI
- Created an interactive dashboard showcasing:
  - Key Marketing KPIs
  - Product-wise and region-wise breakdowns
  - Time-based trends
  - Sentiment distribution
- Built custom DAX measures for business logic and performance tracking

---

## 📌 Key Performance Indicators (KPIs)

- **Conversion Rate**: % of website visitors who made a purchase
- **Engagement Rate**: Interactions with marketing content (clicks, likes, shares)
- **Average Order Value (AOV)**: Average spend per customer transaction
- **Customer Sentiment Score**: Text-based score derived from customer feedback

---

## 🎯 Goals & Insights

### ✅ Increase Conversion Rates
- **Insight**: Drop-offs identified in the product viewing stage.
- **Funnel optimization** is required to retain user interest and push to purchase.

### ✅ Enhance Customer Engagement
- **Insight**: Interactive content (videos, UGC) drives higher click-through and like rates.
- **Social campaigns** outperform traditional email pushes.

### ✅ Improve Customer Sentiment
- **Insight**: Most negative reviews are related to delivery issues.
- **Positive reviews** mention product quality and ease of purchase.

---

## 📌 Recommended Actions

### 🔺 Conversion Rate Optimization
- Focus on high-converting products like **Kayaks**, **Ski Boots**, and **Baseball Gloves**.
- Implement **seasonal promotions** and **targeted campaigns** during high-traffic periods.
- Personalize user journeys based on prior interaction data.

### ⚡ Boost Customer Engagement
- Experiment with **interactive content** (polls, videos, user stories).
- Optimize **CTA placement** in social media and blog content.
- Launch campaigns during **historically low-engagement months** to normalize performance.

### 💬 Improve Customer Feedback
- Analyze negative feedback for recurring issues.
- Establish a **customer follow-up loop** post-resolution to drive review updates.
- Aim to **raise the sentiment score** closer to a 4.0 rating.

---

## 🛠 Tools & Technologies Used

| Tool       | Purpose                                  |
|------------|------------------------------------------|
| **SQL**    | Data extraction, joins, transformations  |
| **Python** | Sentiment analysis using VADER (NLP)     |
| **Power BI** | Dashboard design and visualization     |
| **DAX**    | KPI calculations, custom metrics         |

---

## 🔗 Live Power BI Dashboard

👉 [**View Interactive Report**](https://tinyurl.com/58uzkxar)  


---

## 🖼️ Dashboard Preview


<img width="1193" height="686" alt="Overview" src="https://github.com/user-attachments/assets/f6aec766-e5a3-4ae0-b905-7200082b24b7" />
<img width="1168" height="675" alt="Conversion Details" src="https://github.com/user-attachments/assets/0aec352f-b665-45ad-b76f-243a4ad4d7a7" />
<img width="1184" height="678" alt="Customer Review Details" src="https://github.com/user-attachments/assets/ac87fae9-b5de-4f05-a2b8-0f52f319361b" />
<img width="1178" height="675" alt="Social Media Details" src="https://github.com/user-attachments/assets/1c3fdc9a-a1a8-4c79-aaec-79ebcf26d80e" />




---




