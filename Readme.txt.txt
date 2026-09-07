# Sales Data Analysis

## Project Overview

This project analyzes supermarket sales data to understand sales performance across different branches, cities, product lines, customer types, and genders.

The analysis focuses on identifying sales patterns and understanding which product categories, branches, and customer segments contribute to overall sales.

---

## Objectives

- Analyze overall sales performance across branches and cities.
- Identify the best-performing product lines.
- Compare sales across customer types and genders.
- Understand sales differences between branches and product categories.
- Analyze tax contribution across different customer and product segments.
- Identify relationships between Unit Price, Quantity, and Tax.

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Dataset

The dataset contains supermarket sales transactions with information about:

- Branch and City
- Customer Type
- Gender
- Product Line
- Unit Price
- Quantity
- Tax
- Other transaction-related details

The dataset is used to analyze sales performance and identify patterns across different customer and product segments.

---

## Data Cleaning & Preparation

The following data preparation steps were performed:

- Checked the dataset structure and dimensions.
- Reviewed column names and data types.
- Checked for missing values.
- Checked for duplicate records.
- Created a `Total_sales` feature using Unit Price and Quantity.

---

## Exploratory Data Analysis

The analysis covers:

- Transactions by City
- Transactions by Customer Type
- Transactions by Product Line
- Total Sales by Branch
- Total Sales by Product Line
- Total Sales by Customer Type
- Total Sales by Gender
- Sales by Branch and Product Line
- Total Tax by Gender and Product Line
- Total Tax by Customer Type and Product Line
- Correlation between Unit Price, Quantity, and Tax

---

## Key Insights

- Sales performance varies across branches and product lines.
- Sports & Travel shows strong overall sales performance, while Health & Beauty contributes comparatively lower sales.
- Member customers generate slightly higher total sales than Normal customers.
- Female customers contribute higher total sales than male customers.
- Branch performance differs across product lines, with different branches performing better in different categories.
- Fashion Accessories contributes the highest total tax across several gender and customer-type segments.
- Unit Price and Quantity show almost no linear relationship based on the correlation analysis.
- Tax has only a weak positive relationship with Unit Price and Quantity.

---

## Recommendations

- Focus on better-performing product lines and monitor their sales performance regularly.
- Review lower-performing product lines to identify opportunities for improvement.
- Compare branch-level performance to identify successful sales patterns.
- Monitor Member and Normal customer sales separately to understand customer purchasing patterns.
- Use gender-based sales patterns as a supporting factor when evaluating customer preferences.
- Monitor tax contributions across product lines and customer segments as part of financial reporting.
- Use the findings as a starting point for deeper analysis of customer behavior, product demand, and branch performance.

---

## Conclusion

The analysis provides an overview of sales performance across different branches, cities, product lines, customer types, and genders.

The results show that sales performance varies across product lines and branches, with some categories contributing more strongly to total sales than others. Member customers contribute slightly higher total sales than Normal customers, while female customers contribute higher total sales than male customers.

The analysis also shows differences in tax contribution across product lines, customer types, and genders. The correlation analysis indicates that Unit Price and Quantity have almost no linear relationship, while Tax has only a weak positive relationship with both variables.

Overall, the analysis helps identify important sales patterns and areas that can be considered when making business decisions.