# Retail Sales Analysis and Data Cleaning Project

## Project Overview

This project presents a comprehensive data analysis workflow applied to a retail dataset using Python. The primary goals include data cleaning, exploratory data analysis (EDA), deriving insights through statistical summaries, and visualizing key metrics to support business decisions. The analysis is conducted using NumPy, Pandas, Matplotlib, and Seaborn libraries.

---

## Tools & Technologies

- **Programming Language**: Python 3.x
- **Libraries Used**:
  - `pandas` — data manipulation and analysis
  - `numpy` — numerical operations and categorization
  - `matplotlib` — data visualization
  - `seaborn` — advanced statistical plotting

---

## Data Cleaning Steps

The following preprocessing tasks were performed:

1. **Duplicate Removal**: All duplicate rows were identified and dropped to ensure data integrity.
2. **Missing Value Imputation**:
   - Missing values in the `Item_Weight` column were filled using the **mean weight per `Item_Type`**.
3. **Standardizing Categorical Data**:
   - Cleaned inconsistent entries in `Item_Fat_Content` (e.g., mapping `"LF"` and `"low fat"` to `"Low Fat"`).
4. **Outlier Detection**:
   - Items with **high visibility but low sales** were flagged as potential outliers.

---

## Exploratory Data Analysis (EDA)

### Key Analytical Tasks

- Counted **unique `Item_Type` values** and identified the top 5 most frequent.
- Calculated the **number of unique outlets** and computed the number of years each has been operational (as of 2025).
- Determined **average sales by `Item_Type`** and sorted them in descending order.
- Created a **pivot table** to examine how `Outlet_Size` and `Outlet_Type` influence average sales.
- Identified the **outlet with the highest average rating** and compared its sales performance to others.
- Created a new feature `Item_Age = 2025 - Outlet_Establishment_Year` and analyzed how it correlates with sales.
- Classified rows into **Sales Categories** (`Low`, `Medium`, `High`) using NumPy.
- Built a **correlation matrix** and extracted the strongest relationships among numerical features.

---

## Visualizations

- **Bar Chart**: Average sales by `Outlet_Type` (black-themed for contrast)
- **Line Chart**: `Item_Visibility` vs `Item_Outlet_Sales` using a 500-row sample for readability
- **Pie Chart**: Distribution of `Sales_Category`
- **Heatmap**: Correlation matrix for numerical features

All visualizations follow a consistent **dark theme**, optimized for clarity and professional presentation.

---


## Conclusion

This project demonstrates proficiency in:
- Cleaning and preparing real-world datasets
- Applying statistical and visual analysis to uncover trends
- Deriving actionable business recommendations from raw data

It can serve as a foundational portfolio project for Data Analyst or Business Intelligence roles.

---

## Author

**Saad Attia**  
Data Analyst | Python | SQL | Visualization  
[LinkedIn](https://www.linkedin.com/in/saad-attia-302433246/) • [GitHub](https://github.com/Saad-learning)