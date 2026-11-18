# Analysing-pharmaceutical-sales-data-
https://roadmap.sh/projects/pharmaceutical-sales-data

#Drug Sales Analysis Using Python

# Project Overview

This project focuses on analysing daily drug sales data using Python. The main objective is to identify sales patterns, understand the performance of different drug categories, and analyse changes in sales over time.

The project uses Python libraries such as Pandas for data analysis and Matplotlib for data visualisation.

# Project Objectives

The main objectives of this project are:

1. Calculate the total sales quantities for each drug category (ATC code).
2. Identify the drug categories with the highest total sales.
3. Find the top three selling drug categories in January 2015, July 2016, and September 2017.
4. Identify the highest-selling drug category in 2017.
5. Calculate the average daily sales of each drug category.
6. Analyse the monthly sales patterns of respiratory drugs (R03).

# Dataset Information

The dataset contains daily drug sales information for different drug categories.

Dataset details:
Total observations: 2,106
Total columns: 13
Data type: Daily sales data
Time period: January 2014 to October 2019

Drug categories (ATC codes):
1)M01AB
2)M01AE
3)N02BA
4)N02BE
5)N05B
6)N05C
7)R03
8)R06

The dataset also contains date-related information such as year, month, hour, and weekday name.

# Tools and Technologies Used

 Tool / Library | Purpose 

 Python | Programming language |
 Pandas | Data manipulation and analysis |
 Matplotlib | Data visualization |
 Jupyter Notebook | Writing and executing Python code |
 GitHub | Project storage and version control |

# Data Analysis and Visualisations

The following analysis was performed using Python, Matplotlib, and Pandas.

## Question 1: Total Sales Quantities for Each Drug Category

Calculated the total sales quantity for all eight drug categories using the sum() function.

Visualisation: Bar Chart

Answer: N02BE recorded the highest total sales quantity of approximately 63,005.40.

## Question 2: Drug Categories with the Highest Total Sales

Compared the total sales of different drug categories and arrange them in descending order.

Visualisation: Horizontal Bar Chart

Answer: N02BE recorded the highest sales, followed by N05B and R03.

## Question 3: Top Three Selling Drug Categories in Selected Months

Identified the three highest-selling drug categories for:
January 2015
July 2016
September 2017

Visualisation: Three separate Bar Charts

Answer: N02BE recorded the highest sales in all three selected months.

## Question 4: Highest-Selling Drug Category in 2017

Filtered the dataset for the year 2017 and calculated the total sales of each drug category.

Visualisation: Bar Chart

Answer: N02BE recorded the highest sales in 2017, with approximately 9,258.80.

## Question 5: Drug Category with the Highest Average Daily Sales

Calculated the average daily sales of each drug category using the `mean()` function.

Visualisation: Bar Chart

Answer: N02BE recorded the highest average daily sales of approximately 29.92.

## Question 6: Monthly Sales Pattern of Respiratory Drugs (R03)

Analysed the average sales of respiratory drugs across all twelve months.

Visualisation: Line Chart

Answer:
December recorded the highest average daily sales of approximately 7.92.
October recorded the second-highest average daily sales of approximately 7.21.
July recorded the lowest average daily sales of approximately 2.96.

The results indicate monthly variations in respiratory drug sales.

# Data Visualisation Techniques

The following charts were created using Matplotlib:

1. Bar Chart – To compare total sales across drug categories.
2. Horizontal Bar Chart – To display the top five selling drug categories.
3. Bar Charts – To compare the top three drug categories in selected months.
4. Bar Chart – To compare drug sales during 2017.
5. Bar Chart – To compare average daily sales.
6. Line Chart – To identify monthly sales trends of respiratory drugs.

# Python Concepts Used

The project covers the following beginner-level Python and Pandas concepts:

- Importing libraries
- Loading datasets using read_csv()
- Displaying data using head()
- Selecting columns
- Filtering rows
- Calculating totals using sum()
- Calculating averages using mean()
- Grouping data using groupby()
- Sorting values using sort_values()
- Creating visualisations using Matplotlib
- Using plt.bar(), plt.barh(), and plt.plot()

# Key Findings

- N02BE is the highest-selling drug category overall.
- N05B is the second-highest-selling category.
- N02BE consistently recorded the highest sales in the three selected months.
- N02BE also recorded the highest sales in 2017.
- N02BE has the highest average daily sales.
- Respiratory drug sales (R03) vary across different months, with higher average sales in October and December.

# Conclusion

This project helped in understanding how Python can be used to analyse real-world drug sales data.

Through this analysis, I explored different drug categories, calculated total and average sales, identified the highest-selling categories, and studied monthly sales variations.

The use of Matplotlib helped present the findings through visual representations, making the results easier to understand and interpret.

Overall, this project improved my practical knowledge of Python, Pandas, data analysis, and data visualisation.


# Project Information

Project Name: Drug Sales Analysis Using Python

Domain: Data Analysis

Programming Language: Python

Libraries: Pandas, Matplotlib

Platform: Jupyter Notebook

Project Level: Beginner

---

*This project was created as part of my learning journey in Data Science, with a focus on practical data analysis and visualisation using Python.*
