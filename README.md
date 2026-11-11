# Cybernaut Internship Projects

A comprehensive collection of data science, machine learning, web scraping, and full-stack cybersecurity applications developed during the **Cybernaut Internship** by **Yaadishkumar**.

---

## 📁 Repository Structure

```text
projects/
├── 1st month projects/
│   ├── crypto/
│   │   ├── crypto_prices.csv           # Extracted cryptocurrency dataset
│   │   └── web_scarper.py              # Automated crypto price scraper
│   └── imdb/
│       ├── imdb_top_250.csv            # Extracted IMDb top 250 dataset
│       └── imdb_scraper.py             # IMDb Top 250 movies web scraper
│
└── 2 nd month projects/
    ├── Air Quality Index/
    │   ├── app.py                      # Flask web application for AQI prediction
    │   ├── train_model.py              # Machine learning training pipeline
    │   ├── eda.py                      # Exploratory Data Analysis
    │   ├── clean_dataset.py            # Data cleaning & preprocessing
    │   └── Data/                       # Air quality measurements dataset
    │
    ├── email spam/
    │   ├── app.py                      # Flask web app for real-time spam prediction
    │   ├── notebook.ipynb              # EDA, 5-fold cross validation & evaluation
    │   ├── src/                        # Preprocessing, training, and visualization pipelines
    │   ├── models/                     # Saved models (MultinomialNB, TF-IDF vectorizer)
    │   └── spam.csv                    # SMS/Email spam dataset
    │
    └── phishshift/
        ├── backend/                    # Python Flask REST API & heuristic risk engine
        ├── frontend/                   # React 19 + Vite responsive security scanner UI
        ├── app.py & wsgi.py            # Production WSGI server entrypoints
        └── render.yaml                 # Deployment configuration for Render
```

---

## 🚀 Projects Overview

### 1️⃣ Month 1: Web Scraping & Data Extraction
* **Crypto Price Scraper (`1st month projects/crypto/`):** Python-based scraper extracting live cryptocurrency pricing, market statistics, and exporting structured records to CSV.
* **IMDb Top 250 Scraper (`1st month projects/imdb/`):** Automated scraper fetching ratings, release years, and movie rankings from IMDb's Top 250 chart.

---

### 2️⃣ Month 2: Machine Learning & Full-Stack Security
* **Air Quality Index Predictor (`2 nd month projects/Air Quality Index/`):** An end-to-end environmental data science pipeline predicting AQI levels from particulate matter and atmospheric readings. Includes data cleaning, feature engineering, and a Flask web interface.
* **Email & SMS Spam Classifier (`2 nd month projects/email spam/`):** NLP-driven spam detection comparing **Multinomial Naive Bayes**, **Logistic Regression**, and **LinearSVC** using Stratified 5-Fold Cross-Validation and TF-IDF feature extraction.
* **PhishShift — Message Risk Scanner (`2 nd month projects/phishshift/`):** A full-stack cybersecurity application evaluating messages for smishing, suspicious links, and credential theft with transparent 0–100 threat scoring. Built with **React 19**, **Flask**, and **SQLite**.

---

## 🛠️ General Setup & Installation

Each project includes its own dependencies and instructions:
* Navigate to any project folder (e.g. `cd "2 nd month projects/email spam"`).
* Install requirements using `pip install -r requirements.txt`.
* Run the respective entrypoints (e.g., `python app.py`).
