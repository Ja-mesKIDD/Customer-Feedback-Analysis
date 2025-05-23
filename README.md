# 📝 Customer Feedback Analysis

This project provides an exploratory data analysis (EDA) and natural language processing (NLP) of customer feedback to uncover actionable insights, identify satisfaction drivers, and highlight common issues to enhance customer experience strategies.

## 📁 Project Structure

```
customer-feedback-analysis/
├── EDA GB.ipynb                  # Jupyter Notebook for EDA and NLP
├── customer_feedback.csv         # Customer feedback dataset
└── README.md
```

## 🎯 Objective

To analyze customer feedback data using EDA and NLP techniques in order to:

* Understand customer sentiment
* Identify frequent topics and recurring complaints or praise
* Provide data-driven insights to support service and product improvements

## 🧰 Tools & Libraries

* **Python**: Core programming language
* **Pandas**, **Matplotlib**, **Seaborn**: Data manipulation and visualization
* **NLTK**, **TextBlob**, **WordCloud**: Natural language processing
* **Jupyter Notebook**: Interactive data exploration

## 🔍 Key Analysis Areas

* **Sentiment Analysis**: Using TextBlob to categorize feedback as positive, negative, or neutral
* **Keyword Extraction**: Identifying frequent terms using NLTK tokenization and frequency distribution
* **Word Clouds**: Visualizing the most common words for quick pattern recognition
* **Time-based Trends**: Exploring feedback volume and sentiment over time

## 📈 Sample Insights

* Pinpointed service issues recurring across negative feedback clusters
* Discovered strong emotional language associated with positive reviews
* Identified peak times for negative sentiment—potentially linked to service delays

## 🚀 How to Use

1. Clone this repository
2. Install dependencies (recommended in a virtual environment):

   ```bash
   pip install pandas matplotlib seaborn nltk textblob wordcloud
   python -m textblob.download_corpora
   ```
3. Open and run the notebook:

   ```bash
   jupyter notebook "EDA GB.ipynb"
   ```
4. Replace `customer_feedback.csv` with your own dataset to apply the same workflow.


