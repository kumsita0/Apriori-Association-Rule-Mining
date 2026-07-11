# frequent_pattern_mining->Grocery-Market-Basket-Analysis
Frequent Pattern Mining (FPM) problems to practice Apriori, Support, Confidence, and  Python statements that help in automating scanning of datasets to analyze transactions.

# Market Basket Analysis using Apriori Algorithm

## Project Overview

This project demonstrates **Market Basket Analysis** using the **Apriori Algorithm** in Python. The objective is to identify frequently purchased item combinations and generate association rules that provide insights into customer purchasing behavior.

This project was completed using **Jupyter Notebook** as part of a Data Mining assignment.

---

## Business Problem

Retailers often want to answer questions such as:

- Which products are frequently purchased together?
- How can product placement improve sales?
- Which products should be recommended together?
- Which combinations are useful for promotions?

Association Rule Mining helps answer these questions.

---

## Dataset

The dataset contains grocery shopping transactions where each transaction includes multiple purchased products.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- mlxtend (Apriori)
- Anaconda

---

## Project Workflow

1. Import Libraries
2. Load Grocery Dataset
3. Data Cleaning
4. Exploratory Data Analysis
5. Create Pivot Table
6. One-Hot Encoding
7. Frequent Itemset Mining (Apriori)
8. Generate Association Rules
9. Evaluate Support, Confidence, and Lift
10. Visualize Results

---

## Key Metrics

### Support

Measures how frequently an itemset appears in the dataset.

### Confidence

Measures the likelihood that Product B is purchased when Product A is purchased.

### Lift

Measures the strength of association between products.

- Lift > 1 indicates a positive relationship.
- Lift = 1 indicates no relationship.
- Lift < 1 indicates a negative relationship.

---

## Results

The Apriori algorithm identified meaningful purchasing patterns that can help retailers:

- Improve product placement
- Create promotional bundles
- Increase cross-selling opportunities
- Improve recommendation systems

---

## Repository Structure

```
market-basket-analysis-apriori/
│
├── notebooks/
│   └── Updated_Groceries_dataset.ipynb
│
├── data/
│   └── Groceries_dataset.csv
│
├── images/
├── README.md
└── requirements.txt
```

---

## Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Association Rule Mining
- Apriori Algorithm
- Python Programming
- Data Visualization
- Jupyter Notebook
- Business Analytics

---

## Future Enhancements

- FP-Growth Algorithm
- Interactive Dashboard
- Streamlit Web App
- Product Recommendation Engine

---

## Author

**Kumari Sita**

- Python
- SQL
- R
- Jupyter Notebook
- Anaconda
- Certified Scrum Master (CSM)
- Certified Scrum Product Owner (CSPO)
