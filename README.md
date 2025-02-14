# 🛒 Supermarket Sales Data Analysis

## 📌 Project Overview
This project focuses on **data wrangling and analysis** of a supermarket sales dataset. The goal is to **clean, process, and derive insights** from the data using **Python** and visualization tools.

## 🗂️ Dataset Information
- The dataset contains transaction details from a supermarket.
- Includes **product details, pricing, payment method, customer ratings, and sales information**.
- Some data inconsistencies and missing values were cleaned and handled in the process.

## 🛠️ Data Cleaning Process
### ✅ Steps Taken:
1. **Data Inspection:** Checked for missing values, duplicates, and data types.
2. **Handling Missing & Erroneous Data:**  
   - Filled missing values with **mean/median** where appropriate.
   - Replaced negative values in `Quantity` with the **mean quantity**.
   - Fixed **outliers** in `Total` using the **Interquartile Range (IQR) method**.
3. **Feature Engineering:**  
   - Created `Subtotal` (`Quantity * Unit Price`).
   - Recalculated `Tax 5%` and `Total` for consistency.
4. **Data Visualization:**  
   - **Boxplots & histograms** for data distribution.
   - **Heatmap** for correlation analysis.
   - **Pie chart** for payment method distribution.

## 📊 Business Insights
- The most popular **payment method** is `...` (based on visualization).
- `...` has the highest **total sales**.
- The highest-rated products are in the `...` category.
- The **correlation matrix** shows a strong relationship between `Total` and `Quantity`.

## 🖥️ Technologies Used
- **Pandas**, **NumPy** - Data Manipulation  
- **Matplotlib**, **Seaborn** - Visualization  
- **Jupyter Notebook / VS Code** - Development Environment  
