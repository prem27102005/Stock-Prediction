# Stock Movement Prediction Using Reddit Data

## Overview
This project aims to predict stock price movements by analyzing sentiment and discussion trends from Reddit. The workflow includes scraping posts from stock-related subreddits, preprocessing the text data, performing sentiment analysis, and training machine learning models to forecast stock movements.

The project is divided into three main components:
1. **Data Scraping**: Collect data from Reddit using PRAW (Python Reddit API Wrapper).
2. **Data Preprocessing**: Clean and prepare text data for analysis.
3. **Prediction Model**: Train and evaluate machine learning models using sentiment and other features.

---

## Features
- **Scraper**: Collect posts from Reddit's stock-related subreddits.
- **Text Preprocessing**: Remove noise, perform tokenization, and lemmatize text.
- **Sentiment Analysis**: Extract sentiment polarity and other features.
- **Prediction Model**: Use machine learning models to predict stock price movements.

---

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/stock-movement-prediction.git
cd stock-movement-prediction
Stock-Movement-Prediction/
│
├── scraper/
│   ├── reddit_scraper.py        # Script for scraping Reddit posts
│   ├── requirements.txt         # Dependencies for the project
│
├── notebooks/
│   ├── data_preprocessing.ipynb # Notebook for cleaning and preprocessing data
│   ├── model_training.ipynb     # Notebook for model training and evaluation
│
├── data/
│   ├── reddit_data.csv          # Example scraped Reddit data
│
├── README.md                    # Project documentation and instructions
│
└── .gitignore                   # File to exclude unnecessary files


