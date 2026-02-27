# Data Science Portfolio – Benjamin Kadiri

[![Python](https://img.shields.io/badge/python-3.11-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

This repository showcases projects that blend data engineering, exploratory analysis, and machine learning with a strong emphasis on business context.

Below you'll find an overview of each project — Please click through to the individual READMEs for full details, notebooks, and results.

## 📋 Table of Contents
1. [Web Scraping: Countries of the World](#1️⃣-web-scraping-countries-of-the-world-dataset)
2. [Budget Tracker Project](#2️⃣-budget-tracker-project)
3. [Credit Card Fraud Detection](#3️⃣-credit-card-fraud-detection)
4. [Tools & Technologies](#🚀-tools--technologies)
5. [Focus & Contact](#📈-focus)

The repository contains practical, end-to-end projects demonstrating skills in:

- Data collection & web scraping
- PDF extraction & table parsing
- Data cleaning, quality validation & synthetic dataset design
- Exploratory Data Analysis (EDA) with visualization
- Machine learning, imbalanced classification & model comparison
- Fraud detection modeling and cost‑aware decision making
- Business-oriented analytics and data-driven recommendations

Each project is structured with clear documentation, reproducible notebooks, and insights.

---

## 📂 Projects

### 1️⃣ [Web Scraping: Countries of the World Dataset](web_scraping_countries/README.md)
- Scraped country-level data (population, capital, area) from a public website
- Turned nested HTML into a clean CSV (`World_info.csv`)
- Demonstrates independent data acquisition and handling of non‑standard layouts


---

### 2️⃣ [Budget Tracker Project](budget_tracker/README.md)
This repository is split into two focused components, each with its own README:

- **Bank Statement PDF Extraction & Analysis** – real PDF parsing, data quality validation, and the decision to reject unreliable data. (see `budget_tracker/bank statement/README.md`)
- **Synthetic Data Budget Tracker** – a complete budget system built on clean, dummy transactions, with analysis and visualizations. (see `budget_tracker/synthetic data/README.md`)

Both demonstrate data engineering, validation, and analytical workflow.  


---

### 3️⃣ [Credit Card Fraud Detection](credit_card_fraud/README.md)
- Developed and compared multiple machine learning models (Logistic Regression, Random Forest, Gradient Boosting).
- Focused on imbalanced classification with ROC‑AUC, precision‑recall, and cost‑aware threshold tuning.
- Explored business impacts of false positives/negatives and recommended deployment strategy.


---

## 🚀 Tools & Technologies

The projects primarily use Python and a standard data‑science stack:

- **Data manipulation:** Pandas, NumPy
- **Modeling:** Scikit-learn
- **Visualization:** Matplotlib, Seaborn
- **Web scraping:** requests, BeautifulSoup
- **PDF parsing:** pdfplumber
- **Environment:** Jupyter notebooks (also compatible with Colab)

All dependencies are listed in `requirements.txt` for easy setup.

---

## 📈 Focus

This portfolio emphasizes:
- Real-world data handling and validation
- Model comparison, evaluation, and threshold tuning
- Business-focused thinking in ML applications and decision analysis

---

📬 **Reach Out**
If you'd like to discuss a project, collaborate, or have feedback, feel free to create an issue or contact me via GitHub.

Thank you for visiting!  
