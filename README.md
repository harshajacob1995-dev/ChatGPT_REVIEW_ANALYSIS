ChatGPT Reviews Sentiment Analysis

📌 Project Overview

This project analyzes user reviews of ChatGPT to understand overall sentiment, rating patterns, common issues in negative feedback, and how reviews change over time. The analysis is performed using Python in Google Colab.

🎯 Objectives

Clean and preprocess review data

Perform sentiment analysis on textual reviews

Categorize reviews as Positive, Neutral, or Negative

Analyze the relationship between ratings and sentiment

Identify common phrases in negative reviews

Study review trends over time

🗂 Dataset Description

The dataset (chatgpt_reviews.csv) contains:

review – User review text

ratings – Numerical rating given by users

review_date – Date of the review

Missing values are handled during preprocessing.

🛠 Tools & Libraries Used

Python

Google Colab

Pandas

TextBlob (Sentiment Analysis)

Matplotlib & Seaborn

Regex (re)

Collections (Counter)

🔄 Data Preprocessing

Standardized column names

Handled missing values in review text

Converted review dates to datetime format

Converted ratings to numeric values

Checked data types and null values

🧠 Sentiment Analysis

Calculated sentiment polarity using TextBlob

Classified reviews into:

Positive (polarity > 0.1)

Neutral (between -0.1 and 0.1)

Negative (polarity < -0.1)

📊 Visualizations

Sentiment distribution using bar charts

Rating distribution by sentiment using stacked bar charts

Most common phrases in negative reviews using horizontal bar charts

Review volume over time using line charts

🔍 Negative Review Analysis

Filtered negative reviews

Cleaned text using regex

Extracted frequent bi-grams and tri-grams

Identified top recurring complaint phrases

📈 Time-Based Analysis

Grouped reviews by month

Analyzed trends in review volume over time

✅ Key Insights

Overall sentiment distribution of ChatGPT reviews

Relationship between low ratings and negative sentiment

Frequently mentioned issues in negative reviews

Changes in review volume over time

📂 Project Structure

chatgpt_reviews.csv – Input dataset

sentiment_analysis.ipynb – Python notebook containing the analysis

README.md – Project documentation

🚀 Conclusion

This project demonstrates how natural language processing and data visualization can be used to extract meaningful insights from user-generated text. The analysis helps identify user sentiment trends and common pain points, which can support product improvement decisions.
