# OIBSIP-DataAnalystics-L1-EDARetailSales-
# 📊 Exploratory Data Analysis (EDA) on Retail Sales Data

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a retail sales dataset using Python and popular data analysis and visualization libraries. The main objective is to identify sales patterns, understand customer purchasing behavior, analyze product category performance, and extract actionable business insights from retail transaction data.

The analysis includes data cleaning, descriptive statistics, time-series analysis, customer demographics, product performance, correlation analysis, and data visualization.

## 🎯 Objectives

- Load and inspect the retail sales dataset.
- Identify missing values, duplicate records, and data type inconsistencies.
- Calculate descriptive statistics for numerical variables.
- Analyze monthly and quarterly sales trends.
- Explore customer age-group and gender distributions.
- Identify best-selling products or product categories.
- Analyze revenue contribution by product category.
- Examine relationships between numerical variables using a correlation heatmap.
- Investigate weekday sales patterns.
- Develop actionable business recommendations based on the findings.

## 🛠️ Technologies Used

- **Python** – Programming language for data analysis.
- **Pandas** – Data manipulation, cleaning, and aggregation.
- **NumPy** – Numerical computations.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical visualization and heatmaps.
- **Jupyter Notebook** – Interactive development and documentation.
- **Kaggle** – Dataset source.

## 📂 Dataset

The project uses a retail sales dataset containing transaction-level information.

**Dataset source:** [Retail Sales Dataset on Kaggle](https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset/data)

The commonly used version includes the following columns:

| Column | Description |
|---|---|
| Transaction ID | Unique identifier for a transaction |
| Date | Date of the transaction |
| Customer ID | Identifier for the customer |
| Gender | Recorded customer gender |
| Age | Customer age |
| Product Category | Category of the purchased product |
| Quantity | Number of units purchased |
| Price per Unit | Price per unit |
| Total Amount | Total transaction amount |

*Note: Column names and dataset structure may vary between versions. Refer to the downloaded CSV file for the exact schema.*

## 📁 Project Structure

```text
Retail-Sales-EDA/
│
├── retail_sales_eda.ipynb
├── retail_sales_dataset.csv
└── README.md
```

- `retail_sales_eda.ipynb` — Jupyter Notebook containing the analysis, visualizations, observations, and conclusions.
- `retail_sales_dataset.csv` — Retail sales dataset, if permitted to redistribute.
- `README.md` — Project documentation.

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Retail-Sales-EDA.git
```

### 2. Navigate to the project directory

```bash
cd Retail-Sales-EDA
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Download the dataset

Download the CSV file from the [Kaggle dataset page](https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset/data) and place it in the project directory.

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `retail_sales_eda.ipynb` and execute the cells sequentially.

## 🔍 Exploratory Data Analysis

### 1. Data Loading and Initial Inspection

- Load the CSV file using Pandas.
- Examine dataset dimensions and column names.
- Inspect data types and summary information.
- Identify missing values and duplicate records.
- Clean and prepare data for analysis.

### 2. Descriptive Statistics

Calculate the following statistical measures for numerical columns:

- Mean
- Median
- Mode
- Standard deviation
- Minimum and maximum values

These statistics help understand the distribution and variability of sales and customer-related variables.

### 3. Monthly Sales Analysis

A line chart displays total sales aggregated by month. This analysis helps identify monthly revenue fluctuations, potential peak periods, and opportunities for sales planning.

### 4. Quarterly Sales Analysis

Quarterly sales aggregation provides a broader view of business performance and helps identify changes in revenue across calendar quarters.

### 5. Customer Demographics Analysis

Customer age groups are analyzed to understand the distribution of recorded transactions across different age ranges. Gender-based analysis compares transaction counts, total revenue, and average transaction values.

### 6. Best-Selling Products Analysis

Products are ranked by total units sold when individual product identifiers are available. If the dataset contains only product categories, category-level sales are analyzed instead.

This analysis helps identify high-demand products or categories for inventory planning.

### 7. Revenue by Product Category

A bar chart compares total revenue across product categories. It helps identify the categories contributing the largest share of recorded sales.

### 8. Correlation Heatmap

A correlation heatmap visualizes relationships between numerical variables such as age, quantity, price per unit, and total amount.

This helps identify positive or negative linear associations between variables.

### 9. Additional Visualization: Sales by Day of the Week

A weekday sales chart compares total sales across Monday through Sunday. It helps investigate potential differences in customer activity throughout the week and supports staffing and promotional planning.

## 📈 Key Insights

The notebook is designed to investigate the following questions:

- Which months and quarters generate the highest sales?
- Which customer age groups account for the most transactions?
- How does recorded transaction activity differ by gender?
- Which products or categories have the highest unit sales?
- Which product categories generate the most revenue?
- Which numerical variables exhibit strong correlations?
- Which days of the week show relatively high or low sales?

*The actual findings should be documented here after executing the notebook. Results depend on the dataset and should not be assumed in advance.*

## 💡 Business Recommendations

Based on the patterns identified during analysis, the following actions can be evaluated:

1. **Inventory Optimization:** Use monthly and quarterly sales patterns to plan replenishment and reduce stockouts during periods of high demand.
2. **Product Performance Management:** Prioritize high-volume products and investigate category revenue, costs, and profit margins before changing inventory allocation.
3. **Customer-Focused Marketing:** Test targeted product recommendations and promotional campaigns based on observed purchasing behavior.
4. **Staffing and Promotions:** Evaluate weekday sales patterns to improve staff scheduling and test promotions during lower-demand periods.
5. **Data-Driven Decision-Making:** Track sales, average transaction value, repeat purchases, and inventory turnover to measure the impact of business decisions.

These recommendations should be validated using actual results and subsequent business performance.

## 🏁 Conclusion

This project demonstrates how exploratory data analysis can transform raw retail transaction data into useful business information. Using Python, Pandas, Matplotlib, and Seaborn, the analysis examines sales trends, customer demographics, product performance, and numerical relationships.

The resulting visualizations and statistical summaries provide a foundation for better inventory planning, customer engagement, product management, and sales strategy. The project also demonstrates practical skills in data cleaning, aggregation, statistical analysis, visualization, and business interpretation.

## 🚀 Future Enhancements

- Develop an interactive sales dashboard using Plotly or Power BI.
- Analyze customer retention and repeat purchasing behavior.
- Perform customer segmentation using clustering techniques.
- Forecast future sales using time-series models when sufficient historical data is available.
- Analyze profit margins and discount effectiveness if cost and discount data are available.
- Automate data cleaning and recurring sales reports.

## 👨‍💻 Author

**Your Name**

- GitHub: Natarajan Surya
- Project: Exploratory Data Analysis on Retail Sales Data

## 📄 License and Dataset Attribution

The analysis code may be shared under a license of your choice. The dataset remains subject to its original provider's license and terms. Check the Kaggle dataset license before redistributing the CSV file.

---

⭐ If you find this project useful, consider starring the repository!
