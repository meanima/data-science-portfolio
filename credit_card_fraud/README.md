# Credit Card Fraud Detection

## 📌 Overview
This project delivers a comprehensive analysis of credit card fraud detection using machine learning. The analysis separates signal from noise in European cardholder transaction data, building models that identify fraudulent patterns while minimizing costly false positives. Rather than just achieving high accuracy, the focus is on understanding real-world trade-offs in fraud detection systems.

## 🎯 Objective
- Identify fraudulent transactions within highly imbalanced data (fraud is rare)
- Train and compare multiple machine learning models for classification
- Optimize decision thresholds based on business costs, not just accuracy metrics
- Analyze class imbalance effects and mitigation strategies
- Provide actionable insights for production fraud detection systems

## 📂 Data Source
European credit card transaction dataset - includes both legitimate and fraudulent transactions with anonymized features and transaction metadata.

## 🔍 Methodology

### Data Pipeline & Cleaning
- Robust cross-platform file path handling for reproducibility
- Detection and removal of duplicate transactions
- Validation of data consistency and integrity

### Feature Engineering
- Transformation of raw values into interpretable features
- Extraction of temporal patterns (hour of day, transaction frequency)
- PCA feature analysis for dimensionality understanding

### Exploratory Data Analysis
- Comparative analysis of legitimate vs. fraudulent transaction patterns
- Transaction amount distributions and anomaly detection
- Feature correlation and class imbalance visualization

### Model Development
- **Logistic Regression**: Baseline interpretable model
- **Random Forest**: Ensemble method for capturing complex patterns
- **Gradient Boosting**: Advanced technique for class imbalance handling
- Cross-validation and stratified sampling to handle data imbalance

### Threshold Optimization
- ROC-AUC curve analysis
- Precision-Recall trade-off evaluation
- Confusion matrix analysis across different thresholds
- Cost-benefit analysis for threshold selection

## 📊 Results
- Multiple models compared with clear performance metrics
- Optimal threshold identified based on business cost considerations
- Class imbalance effects quantified and visualized
- Actionable recommendations for production deployment

## 🧠 Key Learnings
- Accuracy alone is misleading with imbalanced datasets
- Decision thresholds matter more than raw model performance
- False positives and false negatives have different business costs
- Ensemble methods (Random Forest, Gradient Boosting) outperform simple baselines
- Real-world system design requires business context, not just statistics

## 🚀 Tools Used
- **Python**: Core analysis language
- **Pandas**: Data manipulation and transformation
- **NumPy**: Numerical computations
- **Scikit-learn**: Machine learning models and evaluation
- **Matplotlib / Seaborn**: Data visualization
- **Jupyter**: Interactive notebook-based analysis
