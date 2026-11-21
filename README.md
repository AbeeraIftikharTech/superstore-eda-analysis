# Superstore Retail Sales - Exploratory Data Analysis (EDA)
Exploratory Data Analysis (EDA) on Superstore retail sales using Python (Pandas, Seaborn). Features data wrangling, seasonality plotting, and discount-sensitivity analysis to identify profit leaks.

## 📌 Project Overview
This repository contains a comprehensive Exploratory Data Analysis (EDA) of the Superstore retail dataset (10,800+ transactions). The project was completed as Task 1 of the Data Analytics & Power BI Internship at Datheon. 

The primary objective was to perform data wrangling, identify missing values, analyze seasonal sales trends, and uncover the root causes of profit leaks—specifically focusing on discount sensitivity.

## 🛠️ Tech Stack
*   **Language:** Python
*   **Libraries:** Pandas, Matplotlib, Seaborn
*   **Environment:** Jupyter Notebook

## 📊 Key Business Insights
1.  **The Discount Trap:** The scatter plot analysis proves that discounts exceeding 20% result in negative profitability across the board.
2.  **Margin Leak:** The Furniture category generated $741K in sales but yielded only $18K in profit.
3.  **Seasonality:** Sales velocity peaks sharply in Q4 (November and December), indicating a strong need for seasonal inventory management.

## 🚀 How to Run
1. Clone this repository.
2. Ensure you have Python and Jupyter Notebook installed.
3. Install the required libraries: `pip install pandas matplotlib seaborn`
4. Open `Superstore_EDA.ipynb` and run the cells.

## 📈 Next Steps
The insights from this EDA will be used to build an interactive executive dashboard in Power BI (Task 2).
