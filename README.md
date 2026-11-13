# customer-retention-analysis
Customer retention, purchasing behavior, and RFM segmentation analysis using Python, statistical testing, and Power BI.
## Project Overview
# Customer Retention & Value Analysis

## Project Overview

An end-to-end data analytics project focused on customer retention, repeat purchase behavior, and customer lifetime value using the Online Retail II dataset. The project explores how first-purchase characteristics relate to customer retention, examines purchasing patterns, and segments customers based on frequency and monetary value.

## Business Objectives

- Analyze customer retention and repeat purchase behavior.
- Identify factors associated with repeat purchases within 90 days.
- Explore the relationship between purchase frequency and customer revenue.
- Segment customers using Frequency × Value and RFM analysis.
- Evaluate the predictive power of first-purchase characteristics.
- Develop data-driven business recommendations.

## Dataset

**Online Retail II**

- 1,067,371 original transaction records.
- 5,878 unique customers.
- 36,969 unique orders.
- Time period: December 2009 – December 2011.

Source: [Online Retail II Dataset – UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/502/online+retail+ii)

## Tools & Technologies

- **Python:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Statistical Analysis:** SciPy (Mann–Whitney U test)
- **Machine Learning:** Scikit-learn (Logistic Regression)
- **SQL:** DuckDB
- **Business Intelligence:** Power BI
- **Environment:** Jupyter Notebook

## Project Workflow

1. **Data Cleaning & Preparation** – Removed duplicates, excluded cancelled transactions and invalid sales records, and handled missing customer identifiers.
2. **Exploratory Data Analysis (EDA)** – Examined customer purchasing behavior, order frequency, and revenue distribution.
3. **Customer Retention Analysis** – Analyzed repeat purchases across different time windows and evaluated 90-day retention.
4. **Statistical Testing** – Applied Mann–Whitney U tests to investigate differences in first-order revenue and quantity.
5. **Customer Segmentation** – Performed Frequency × Value and RFM segmentation.
6. **Predictive Modeling** – Built a Logistic Regression model to assess whether first-purchase characteristics could predict repeat purchases.
7. **Power BI Dashboard** – Developed visual reports to communicate findings and business insights.

## Key Findings

| Metric | Result |
|---|---:|
| 90-day repeat purchase rate | 47.1% |
| Q4 vs Q1 repeat purchase rate difference | +21.4 percentage points |
| Order frequency and total revenue correlation | 0.628 |
| Revenue share of High Frequency / High Value segment | 86.5% |
| Logistic Regression ROC-AUC | 0.595 |

### Business Insights

- Customers with higher first-order revenue showed a higher observed repeat purchase rate.
- Purchase frequency was positively associated with total customer revenue.
- Frequency alone did not fully capture customer value.
- First-purchase characteristics provided limited predictive power for identifying future repeat customers.
- Retention initiatives and customer segmentation could help businesses better understand and engage different customer groups.

## Repository Contents

- `customer_retention_analysis.ipynb` – Python analysis, statistical testing, SQL queries, and predictive modeling.
- `customer_retention_dashboard.pbix` – Interactive Power BI dashboard.
- `customer_retention_presentation.pdf` – Project findings, visualizations, and business recommendations.

## Limitations

The analysis identifies statistical associations rather than causal relationships. The predictive model achieved a ROC-AUC of 0.595, indicating limited predictive performance.

## Author

**Laura Yerezhepova**

Data Analyst | Python | SQL | Power BI
