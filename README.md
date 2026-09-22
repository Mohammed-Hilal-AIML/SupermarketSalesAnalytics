# Supermarket Sales Analytics with AI

**Student:** Mohammed Hilal  
**Degree:** B.E. Computer Science & Engineering (AI & ML)  
**Institution:** Nawab Shah Alam Khan College of Engineering & Technology, Hyderabad  
**Internship:** AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026

## Project Description

This project analyzes supermarket transaction data to identify sales trends, product/category performance, branch performance, customer behavior and business opportunities. It also demonstrates customer-level RFM feature engineering and a leakage-aware Logistic Regression churn model.

The project follows the internship learning flow:

**Raw Data → Clean Data → EDA → Insights → Prediction → Business Action**

## Dataset

The notebook can load a local file named `supermarket_sales.csv`.

For a reference supermarket-sales dataset, see the Kaggle Supermarket Sales resources:
https://www.kaggle.com/code/nileshiq/supermarket-sales-analytics

If the CSV is not present, the notebook creates a reproducible 500-row demonstration dataset so that the project can still be executed for academic demonstration.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Analytics Covered

1. Data loading and validation
2. Missing-value handling
3. Duplicate checking
4. Data-type conversion
5. KPI calculation
6. Monthly sales analysis
7. Category and product analysis
8. Branch and regional analysis
9. Customer-type analysis
10. RFM feature engineering
11. Churn classification
12. Confusion matrix
13. Accuracy, precision, recall and F1-score
14. Business insights and recommendations

## Project Structure

```text
Mohammed_Hilal_Supermarket_Sales_Analytics/
├── MohammedHilal_SupermarketSalesAnalytics.ipynb
├── requirements.txt
├── README.md
└── MohammedHilal_SupermarketSalesAnalytics_ProjectReport.docx
```

## Setup

### 1. Install Python

Python 3.10+ is recommended.

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

```bash
jupyter notebook
```

Open:

`MohammedHilal_SupermarketSalesAnalytics.ipynb`

Run the cells from top to bottom.

## Dataset option

If you have the internship-provided CSV, place it in the same folder and name it:

```text
supermarket_sales.csv
```

The notebook will automatically use it.

## Important ML Note

The notebook demonstrates target-leakage awareness. Because a demonstration churn label is defined from recency, `Recency` is not directly supplied to the Logistic Regression model. For a production-grade churn system, the target should be created from a future observation period rather than from the same snapshot used to calculate features.

## Student Profile

Mohammed Hilal is a B.E. CSE (AI & ML) graduate with a focus on Python, machine learning, NLP and GenAI. Relevant project experience includes Resume Parser using LangChain/GenAI, ML classification projects and NLP-based applications.
