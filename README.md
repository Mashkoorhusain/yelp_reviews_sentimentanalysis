# 📊 Yelp Review Sentiment Analysis Using Python, AWS S3 & Snowflake

## 📝 Project Overview

This project showcases an end-to-end data pipeline and analysis workflow for a large-scale Yelp reviews dataset. 
The goal was to ingest, store, and analyze unstructured JSON data to uncover business insights using sentiment analysis and advanced SQL techniques.

---

## ⚙️ Tech Stack
- **Python**: For data parsing, transformation, and sentiment analysis (using `TextBlob`)
- **AWS S3**: Cloud storage for scalable, secure data handling
- **Snowflake**: Cloud data warehouse used for querying and analysis
- **SQL**: For business problem-solving using CTEs, window functions, and ranking logic

---

## 🧪 Steps Involved

### 1. 📥 Data Ingestion & Preparation
- Worked with a **very large JSON dataset** (Yelp open dataset)
- Used Python to:
  - Break the massive file into smaller, manageable chunks
  - Clean and preprocess the data
  - Perform sentiment analysis using the `TextBlob` library

### 2. ☁️ Cloud Storage on AWS S3
- Uploaded the cleaned and chunked data to **Amazon S3** buckets
- Ensured folder structure for efficient data loading

### 3. 🧊 Loading into Snowflake
- Connected Snowflake to AWS S3 via external stage
- Loaded data into structured Snowflake tables
- Handled JSON parsing and flattening within Snowflake

### 4. 🔍 Analysis Using Advanced SQL
- Performed complex analysis using:
  - **CTEs (Common Table Expressions)**
  - **Window functions** (e.g., `ROW_NUMBER`, `RANK`)
  - **Sentiment aggregation and filtering**
- Solved business problems like:
  - Top businesses by 5-star reviews
  - Sentiment trends by category
  - Average sentiment polarity across locations

---

## 📈 Example Business Questions Answered
- Which businesses have the highest proportion of positive reviews?
- How do sentiment trends vary across different cities or business categories?
- What’s the average sentiment polarity of top-reviewed businesses?

---

## 💡 Key Learnings
- Handling massive JSON datasets with Python
- Integrating AWS S3 with Snowflake for scalable data warehousing
- Writing efficient and readable SQL for business insights
- Performing sentiment analysis using natural language processing (NLP)

---

## 🚀 Future Improvements
- Deploy sentiment dashboard using Power BI or Streamlit
- Automate pipeline using AWS Lambda or Airflow
- Extend sentiment scoring to include subjectivity

---

## 📬 Let's Connect
If you found this interesting or have questions, feel free to connect on [LinkedIn]([https://www.linkedin.com/](https://www.linkedin.com/in/mashkoorhusain-husaini-728414305/)) 
or reach out!
