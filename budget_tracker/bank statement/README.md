# Bank Statement PDF Extraction & Analysis

## 📌 Overview
This component extracts transaction data from real bank PDF statements and performs rigorous data quality validation. It demonstrates critical thinking in data science — knowing when data is unfit for reliable analysis despite careful cleaning efforts.

## 🎯 Objective
- Extract structured transaction tables from PDF bank statements
- Validate data consistency and integrity
- Identify duplicates and anomalies
- Assess data reliability for financial analysis

## 🔍 Methodology
- **PDF Parsing**: Extract tables using `pdfplumber`
- **Data Cleaning**: Remove duplicates, handle missing values
- **Validation**: Cross-check transactions, verify balances
- **Quality Assessment**: Document inconsistencies and limitations

## 📊 Key Findings
The extracted data revealed multiple inconsistencies and potential duplicates that compromised reliability. After thorough investigation, the dataset was **deemed unsuitable** for production financial analysis—a critical finding that prevented faulty conclusions.

## 🧠 Key Learnings
- Real-world financial data requires exceptionally rigorous validation
- Not all data can be salvaged through cleaning
- Identifying bad data is more valuable than forcing analysis
- PDF extraction demands verification against source documents

## 🚀 Tools Used
- **PDFPlumber**: PDF table extraction
- **Pandas**: Data validation and analysis
- **Python**: Scripting and processing
