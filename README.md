# Black-Friday-Sales-Data-Analysis
This project involves analyzing Black Friday sales data to extract meaningful insights about customer behavior, purchasing patterns, and product popularity. The analysis was conducted using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

Dataset

The dataset used in this project contains information on customer demographics, product details, and purchase amounts. Key columns include:

  User_ID: Unique identifier for each customer\
  Product_ID: Unique identifier for each product\
  Gender: Gender of the customer\
  Age: Age group of the customer\
  Occupation: Occupation code of the customer\
  Marital_Status: Marital status of the customer\
  Product_Category_1: Primary product category\
  Product_Category_2: Secondary product category\
  Product_Category_1: Tertiary product category

## Analysis Summary
1. Analyzing Columns

    Objective: Identify the unique values in each column.\
    Tools: unique() and nunique() functions.\
    Outcome: Gained an understanding of the variety of data, such as total customers and products.

2. Analyzing Gender

    Objective: Analyze the purchasing patterns based on gender.\
    Tools: groupby(), pie charts, and bar plots.\
    Outcome: Found that male customers dominate the dataset and explored which gender makes more purchases.

3. Analyzing Age & Marital Status

    Objective: Explore purchasing trends by age group and marital status.\
    Tools: groupby(), pie charts, and bar plots.\
    Outcome: Identified the age group with the most purchases and the marital status distribution (60% unmarried, 40% married).

4. Multi-Column Analysis

    Objective: Combine multiple columns for more complex analysis.\
    Tools: Seaborn library with the hue parameter.\
    Outcome: Visualized the relationship between Age and Gender, uncovering deeper insights into purchasing behavior.

5. Occupation and Products Analysis

    Objective: Analyze the Occupation, Product_ID, and Product_Category_1 columns.\
    Tools: Countplots, bar plots, groupby() function.\
    Outcome: Gained insights into which occupations purchase the most and identified the most popular products.

6. Combining Gender & Marital Status

    Objective: Explore the combined impact of Gender and Marital Status on purchasing behavior.\
    Tools: Seaborn countplots.\
    Outcome: Discovered meaningful insights by combining these two demographic factors.

## Visualization Examples

The analysis includes various visualizations such as:

  Pie Charts: For gender distribution and marital status.\
  Bar Plots: To show purchasing patterns across different age groups and product categories.\
  Countplots: To explore data distribution across occupations and product categories.

## Conclusion

This project successfully uncovered key insights into customer demographics and purchasing behavior during Black Friday sales. By analyzing various aspects of the dataset, including gender, age, marital status, occupation, and product preferences, we gained a deeper understanding of the factors influencing customer decisions.

Key findings include:

  Gender Trends: Male customers were more prevalent and made more purchases than female customers.\
  Age Group Insights: Certain age groups, particularly younger customers, exhibited higher purchasing activity and total spending.\
  Marital Status: The majority of the customers were unmarried, and their purchasing patterns differed from those who were married.\
  Occupation Analysis: Certain occupations were more associated with higher purchasing volumes, indicating potential target markets.\
  Product Preferences: Specific products and categories were more popular, revealing consumer preferences and trends.

These insights can inform targeted marketing strategies, help businesses tailor their product offerings, and enhance customer engagement during future sales events. Overall, this analysis provides a valuable foundation for optimizing business decisions and driving better outcomes during high-traffic shopping periods like Black Friday.
