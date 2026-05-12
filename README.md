# 📰 End-to-End News ETL Pipeline using Azure Databricks

## 📌 Project Overview

Built an end-to-end ETL pipeline using Azure Databricks and Python to extract entertainment news data from NewsAPI, transform and clean the data, perform NLP-based sentiment analysis, and store the processed data for analytics and reporting.

The pipeline automates news ingestion, full article extraction, text preprocessing, sentiment classification, and workflow scheduling using Databricks.

---

## ⚙️ Tech Stack

- 🚀 Azure Databricks
- 🐍 Python
- 📊 Pandas
- 🔥 PySpark
- 🧠 NLTK (NLP & Sentiment Analysis)
- 📰 NewsAPI
- 📄 newspaper3k
- 💾 Delta Lake
- ⏰ Databricks Workflows

---

## 🔄 Pipeline Flow

```text
NewsAPI
   ↓
Data Extraction
   ↓
Data Cleaning & Transformation
   ↓
Full Article Extraction
   ↓
NLP Processing
   ↓
Sentiment Analysis
   ↓
Delta Table Storage
   ↓
Databricks Workflow Automation
```

---

## ✨ Key Features

✅ Automated ETL Pipeline  
✅ NLP-based Sentiment Analysis  
✅ Full Article Content Extraction  
✅ Word Count Analysis  
✅ Databricks Workflow Scheduling  
✅ Delta Table Storage  
✅ Clean and Structured Output for Analytics  

---

## 📊 Final Output

The pipeline generates a processed dataset containing:

- News Source
- Article Title
- Author
- Published Date
- Full Article Content
- Word Count
- Sentiment (Positive / Neutral / Negative)
- Compound Sentiment Score

---

## 🚀 Future Enhancements

- Implement Medallion Architecture
- Add Real-Time Streaming
- Integrate Power BI Dashboard
- Advanced NLP & ML Models
- Monitoring & Alerting
