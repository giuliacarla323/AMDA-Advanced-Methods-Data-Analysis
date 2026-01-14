# Analyzing the Strengths and Limitations of Naïve Bayes in Text Classification

This project examines the performance of the Naïve Bayes classifier for Natural Language Processing tasks using three datasets that gradually increase in difficulty.

## 🎯 Objectives
The primary goal was to evaluate how preprocessing choices, text representations (Count vs. TF-IDF), and feature configurations influence the model's performance in different scenarios.

## 📊 Datasets
The analysis was performed on:
- **Restaurant Reviews**: Sentiment analysis on short, focused texts.
- **News Topics (AG News)**: Multi-class classification for topic identification.
- **IMDb Movie Reviews**: Complex sentiment analysis involving linguistic nuance.

## 🛠️ Methodology & Implementation
- **Preprocessing**: Tokenization, stop word filtering, and lemmatization.
- **Vectorization**: Comparative analysis between **Count Vectorization** and **TF-IDF**.
- **Model**: Naïve Bayes implementation focused on understanding the impact of the independence assumption.

## 📈 Key Findings
- Naïve Bayes remains a highly efficient baseline for text classification, particularly for sentiment-focused and short texts.
- Performance is negatively influenced when linguistic nuance or context dependence is critical, due to the feature independence assumption.
- Results indicate that TF-IDF often improves performance in multi-class scenarios compared to simple frequency counts.
