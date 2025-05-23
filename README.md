# 📝 Customer Feedback Analysis

This project combines exploratory data analysis (EDA) and natural language processing (NLP) to derive insights from customer feedback data. It aims to identify key themes, sentiment trends, and actionable recommendations for improving customer experience and operational reliability.

## 📁 Project Structure

```
customer-feedback-analysis/
├── EDA GB.ipynb                       # Jupyter Notebook for EDA and NLP
├── customer_feedback.csv             # Raw customer feedback dataset
├── Customer Feedback Presentation.pdf # Final presentation of findings and insights
└── README.md
```

## 🎯 Objective

To analyze customer feedback using both EDA and NLP techniques in order to:

* Detect and interpret sentiment trends
* Uncover recurring themes in praise and complaints
* Provide evidence-based insights for service and product optimization

## 🧰 Tools & Libraries

* **Python**: Core analysis language
* **Pandas**, **Matplotlib**, **Seaborn**: For data cleaning and visualization
* **NLTK**, **TextBlob**, **WordCloud**: For sentiment analysis and text mining
* **Jupyter Notebook**: Interactive exploration

## 🔍 Key Analysis Areas

* **Sentiment Classification**: Categorizing feedback into positive, negative, and neutral sentiment
* **Keyword Extraction**: Identifying recurring themes and high-impact topics
* **Word Clouds**: Quick visualization of frequent feedback terms
* **Time-Based Patterns**: Exploring when feedback spikes and sentiment shifts

## 📈 Key Insights

* **Customer Satisfaction**: 86% of feedback indicates high satisfaction (NPS scores 8+), but critical issues still affect a minority of users (scores 4–6).
* **Recurring Issues**:

  * False alarms in system alerts
  * Software reliability concerns
  * Slow emergency support response
  * Delays in hardware/equipment replacements
* **Feature Feedback**:

  * Seismic sensor received strong approval (99% positive sentiment)
  * Predictive analytics and real-time alerts need improvement to reduce false positives

## ✅ Recommended Actions

* **Enhance Support & SLAs**: Introduce a tiered response system with strict resolution times (e.g., 24-hour target for hardware issues)
* **Reduce False Alarms**: Recalibrate radar systems and improve predictive analytics models for greater alert accuracy
* **Proactive Maintenance**: Schedule routine on-site maintenance and ensure quicker equipment replacements

## 🖼 Presentation

Key findings and visuals are summarized in
📄 **[Customer Feedback Presentation.pdf](./Customer%20Feedback%20Presentation.pdf)**

## 🚀 How to Use

1. Clone this repository
2. Install dependencies:

   ```bash
   pip install pandas matplotlib seaborn nltk textblob wordcloud
   python -m textblob.download_corpora
   ```
3. Launch the notebook:

   ```bash
   jupyter notebook "EDA GB.ipynb"
   ```
4. Review and customize the analysis for your own feedback dataset
