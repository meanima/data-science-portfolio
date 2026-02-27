# Budget Tracker Project

## 📌 Overview
This project demonstrates practical budget tracking and financial analysis through two complementary approaches: extracting and analyzing real bank statement data from PDFs, and building a working budget tracking system with clean synthetic data. It showcases both critical data validation skills and practical data science implementation.

## 🎯 Objective
- Extract structured financial data from real-world bank PDF statements
- Validate data quality and identify inconsistencies in transaction records
- Build a functional budget tracking system using reliable data
- Perform transaction categorization and spending analysis
- Demonstrate the balance between idealistic data science and practical data validation

## 📂 Data Sources
- **Bank Statement Analysis**: Real PDF bank statements (privacy-preserved)
- **Synthetic Data Analysis**: Clean, dummy transaction data for budget tracking demonstration

## 🔍 Methodology

### A. Bank Statement PDF Extraction
- **PDF Parsing**: Using `pdfplumber` to extract tables and structured data from bank statements
- **Data Quality Assessment**: Identifying duplicates, missing values, and inconsistencies
- **Validation**: Cross-checking extracted data against expected patterns and ledger balances
- **Conclusion**: Data validation revealed inconsistencies that made the dataset unreliable for production analysis

**Key Finding**: This component demonstrates critical thinking—recognizing that sometimes real-world data is unfit for analysis and knowing when to halt rather than force conclusions.

### B. Synthetic Budget Tracking System
- **Data Structuring**: Creating well-formed transaction datasets with proper categorization
- **Analysis Pipeline**: Building repeatable workflow for budget analysis and visualization
- **Financial Metrics**: Calculating spending patterns, category breakdowns, and trends
- **Visualization**: Creating clear charts for spending analysis and budget monitoring

## 📊 Results
- **Bank Statement Component**: Documented findings on data quality issues and validation challenges
- **Synthetic Data Component**: Functional budget tracking system with transaction analysis and spending visualizations
- Combined insights demonstrating both technical challenges in real data and benefits of clean data work

## 🧠 Key Learnings
- Not all data is suitable for analysis even with cleaning efforts
- PDF extraction requires careful validation and verification steps
- Data quality assessment is as important as analysis itself
- Synthetic data provides valuable insights for system design and benchmarking
- Financial data demands particularly rigorous validation and consistency checks
- Practical data science includes knowing when to reject data sources

## 🚀 Tools Used
- **Python**: Core analysis language
- **Pandas**: Data manipulation and transformation
- **PDFPlumber**: PDF extraction and table parsing
- **Matplotlib / Seaborn**: Data visualization and financial charts
- **Jupyter**: Interactive notebook-based analysis

## 📂 Project Structure
- `bank statement/`: PDF extraction and data quality validation
- `synthetic data/`: Budget tracking system with clean data
- `synthetic_budget_transactions_6_months.csv`: Sample synthetic dataset
