# youtube-comment-analyzer
This repository contains a machine learning pipeline developed for a Datathon project. It analyzes YouTube comments stored in CSV datasets (not connected to the YouTube API). The goal is to turn raw, noisy comments into business insights that beauty brands can use to understand engagement, sentiment, and trends.

## Features

Data Preprocessing – Cleans text, removes duplicates, and filters out emojis and links.

Spam Detection – Logistic Regression + rule-based filtering to remove irrelevant comments. Train on UCI Youtube Comments Dataset

Categorization – Rule-based tagging into skincare, makeup, fragrance, or other.

Multi-class Classification – Fine-tuned DistilBERT model for deeper topic recognition.

Sentiment Analysis – Uses RoBERTa (English) and XLM-RoBERTa (multilingual) for emotion detection.


## Dataset

Comments and video metadata were provided by the Datathon organizers in CSV format.

No live scraping or YouTube API integration.

## Future Work

Expand to competitor benchmarking across multiple brand channels.

Use trend prediction to detect rising product interests (e.g., SPF skincare, hyaluronic acid serums).

Connect with brand databases and dashboards for real-time insights.

## Tools & Frameworks

Python, Pandas, Scikit-learn, Transformers (HuggingFace), Streamlit

Models: Logistic Regression, DistilBERT, RoBERTa, XLM-R
