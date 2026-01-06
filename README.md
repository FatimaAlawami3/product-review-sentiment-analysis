# Product Review Sentiment Analysis with NLP

## Overview

This project applies **Natural Language Processing (NLP)** techniques to perform **sentiment analysis on Amazon customer product reviews**. The goal is to automatically extract customer opinions from e-commerce platforms and transform large volumes of textual feedback into **actionable business insights**.

The project focuses on **Amazon reviews of the Apple iPhone 4 (32GB)** and demonstrates how AI can support data-driven decision-making for online sellers and platforms through sentiment classification and visualization.

---

## Problem Statement

Online platforms contain massive numbers of customer reviews that are difficult to analyze manually. Businesses often struggle to:

* Understand overall customer satisfaction
* Identify recurring product strengths and weaknesses
* Extract meaningful insights efficiently

This project addresses these challenges by automating sentiment analysis on Amazon reviews and presenting results through intuitive visualizations.

---

## Dataset

* **Platform:** Amazon
* **Product:** Apple iPhone 4 (32GB)
* **Total reviews:** 1,007
* **Attributes:** review text, rating, review title, review date, product category, sentiment label
* **Review length:**

  * Minimum: 1 character
  * Maximum: 2,572 characters
  * Average: ~164 characters

The dataset provides diverse user opinions suitable for sentiment trend analysis.

---

## Methodology

### 1. Data Preprocessing

* Removed missing and irrelevant entries
* Standardized text format for analysis

### 2. Sentiment Analysis

* Used **TextBlob** polarity scores
* Classified reviews into:

  * **Positive**
  * **Neutral**
  * **Negative**

### 3. Visualization

To better understand sentiment trends, multiple visualizations were generated:

* Histogram of review lengths
* Bar chart showing sentiment distribution
* Pie chart illustrating sentiment proportions

---

## Results Summary

* **Positive reviews:** 55.7%
* **Neutral reviews:** 37.9%
* **Negative reviews:** 6.4%

### Key Insights

* **Strengths:** usability, reliability, and long-term performance
* **Weaknesses:** hardware-related issues (e.g., home button problems)
* **Opportunities:** neutral reviews indicate areas for enhanced customer engagement

These findings demonstrate how sentiment analysis on Amazon reviews can guide product improvement, seller response strategies, and marketing decisions.

---

## Project Structure

```
├── notebooks/
│   └── sentiment_analysis.ipynb
│
├── report/
│   └── ARTI402_Project_Report.pdf
│
├── README.md
└── requirements.txt
```

---

## Tools and Technologies

* Python
* Pandas
* TextBlob
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Key Learning Outcomes

* Applying NLP for real-world sentiment analysis
* Converting unstructured text into structured insights
* Using visualization to support decision-making
* Understanding limitations of rule-based sentiment analysis tools

---

## Team

This project was completed as a **university group project** for **ARTI402 – Programming for AI**.

---

## Future Work

* Replace rule-based sentiment analysis with transformer-based models
* Improve handling of sarcasm and mixed sentiments
* Extend analysis to multiple products and platforms
* Incorporate aspect-based sentiment analysis
