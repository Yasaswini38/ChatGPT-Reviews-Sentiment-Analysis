# ChatGPT Reviews Sentiment Analysis

## Project Overview

This project analyzes customer reviews of ChatGPT to understand user satisfaction, identify sentiment patterns, and extract frequently mentioned positive and negative aspects. Natural Language Processing (NLP) techniques are used to perform sentiment analysis, while data visualization helps uncover meaningful insights from user feedback.

---

## Business Problem

ChatGPT receives thousands of customer reviews from users worldwide. Manually analyzing these reviews is difficult and time-consuming. This project aims to automatically analyze review sentiment and identify the key factors driving positive and negative user experiences.

---

## Project Objectives

* Analyze overall customer sentiment toward ChatGPT.
* Measure sentiment polarity and subjectivity.
* Categorize reviews into Positive, Negative, and Neutral sentiments.
* Identify frequently mentioned keywords in customer feedback.
* Visualize trends and patterns using charts and word clouds.
* Generate actionable insights and recommendations.

---

## Dataset Information

The dataset contains customer reviews with the following attributes:

| Column Name | Description              |
| ----------- | ------------------------ |
| Review Id   | Unique review identifier |
| Review      | Customer review text     |
| Ratings     | User rating (1–5)        |
| Review Date | Date of review           |

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* TextBlob
* WordCloud

---

## Project Workflow

### 1. Data Preparation

* Loaded the dataset.
* Standardized column names.
* Handled missing values.
* Converted ratings to numeric format.
* Converted review dates into datetime format.

### 2. Feature Engineering

Created additional features:

* Review Length
* Word Count
* Review Month

### 3. Sentiment Analysis

Used TextBlob to calculate:

* Polarity
* Subjectivity

Sentiment Classification Rules:

* Positive → Polarity > 0
* Negative → Polarity < 0
* Neutral → Polarity = 0

### 4. Exploratory Data Analysis

Performed analysis on:

* Rating Distribution
* Sentiment Distribution
* Polarity Distribution
* Subjectivity Distribution
* Rating vs Sentiment Relationship

### 5. Keyword Analysis

Extracted common words from:

* Positive Reviews
* Negative Reviews

Generated:

* Word Clouds
* Frequency Visualizations

---

## Visualizations

### Rating Distribution

Shows how users rated ChatGPT.

### Sentiment Distribution

Displays the proportion of positive, neutral, and negative reviews.

### Polarity Distribution

Illustrates how positive or negative customer opinions are.

### Subjectivity Distribution

Shows whether reviews are opinion-based or fact-based.

### Word Clouds

Highlights the most frequently used words in positive and negative reviews.

---

## Key Insights

### Positive Findings

* Majority of customer reviews are positive.
* Users frequently praise ChatGPT's helpfulness and productivity benefits.
* Coding assistance and problem-solving capabilities are highly appreciated.

### Negative Findings

* Some users report incorrect responses.
* Reliability and consistency remain areas for improvement.
* A small percentage of users express dissatisfaction with answer accuracy.

---

## Recommendations

1. Improve response consistency.
2. Reduce factual inaccuracies.
3. Continue enhancing coding assistance capabilities.
4. Focus on reliability improvements for complex queries.

---

## Conclusion

The analysis indicates that ChatGPT enjoys strong overall customer satisfaction. Positive reviews significantly outweigh negative feedback, demonstrating the platform's value to users. While most users appreciate its productivity and assistance capabilities, improvements in accuracy and consistency can further enhance user experience.

---

## How to Run

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn textblob wordcloud
```

### Run Notebook

Open:

```text
notebooks/ChatGPT_Sentiment_Analysis.ipynb
```

and execute all cells.

---

## Author

Yasaswini Padamati

Data Analytics Project – ChatGPT Reviews Sentiment Analysis
