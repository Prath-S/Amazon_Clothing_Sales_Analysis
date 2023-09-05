# Amazon Clothing Sales Data Analysis 📈

Welcome to my personal Amazon clothing sales data analysis project! In this endeavor, I dived into the world of e-commerce, exploring key insights from Amazon sales data. Below, you'll find a comprehensive overview of my dataset, the tools I used, data cleaning procedures, exploratory data analysis (EDA), data visualization steps, and concluding thoughts.

## Table of Contents
1. [Dataset Description](#dataset-description)
2. [Libraries and Tools Used](#libraries-and-tools-used)
3. [Data Cleaning](#data-cleaning)
4. [Exploratory Data Analysis](#exploratory-data-analysis)
5. [Data Visualization](#data-visualization)
6. [Conclusion](#conclusion)

## Dataset Description 📊

My dataset contains records of Amazon clothing sales data. It comprises the following vital attributes:

- **Category**: Type of product. (String)
- **Size**: Size of the product. (String)
- **Date**: Date of the sale. (Date)
- **Status**: Status of the sale. (String)
- **Fulfilment**: Method of fulfilment. (String)
- **Style**: Style of the product. (String)
- **SKU**: Stock Keeping Unit. (String)
- **ASIN**: Amazon Standard Identification Number. (String)
- **Courier Status**: Status of the courier. (String)
- **Qty**: Quantity of the product. (Integer)
- **Amount**: Amount of the sale. (Float)
- **B2B**: Business-to-business sale. (Boolean)
- **Currency**: The currency used for the sale. (String)

By understanding these attributes, we can empower data-driven decisions and optimize our product offerings on the Amazon platform. For a detailed dataset structure, please refer to the dataset file.

## Libraries and Tools Used 🛠️

My data analysis journey was made possible by leveraging the following Python libraries and tools:

- **Python** 🐍: The primary programming language for data analysis and scripting.
- **Pandas** 🐼: For data manipulation, cleaning, and preprocessing.
- **NumPy** 🔢: Empowering numerical operations and calculations.
- **Matplotlib** 📊: Crafting static, interactive visualizations.
- **Seaborn**🌈: Elevating Matplotlib plots' aesthetics and creating informative statistical graphics.
- **Jupyter Notebook** 📓: As my interactive environment for analysis and documentation.

These tools collectively facilitated effective data exploration, visualization, and the presentation of my findings.

## Data Cleaning 🧹

My project commenced with data preparation, encompassing data loading and cleaning. I loaded the dataset using Pandas, and columns were cleaned and formatted for analysis. Data cleaning was a meticulous process, including:

- Standardizing column names for consistency.
- Handling missing values by imputation or row removal.
- Ensuring correct data types for each attribute.
- Verifying data integrity through integrity checks.
- Removing duplicate rows to maintain data integrity.
- Cleaning and ensuring consistency in categorical data.

Through these data cleaning steps, I ensured that my dataset was primed for exploratory data analysis.

## Exploratory Data Analysis 🕵️‍♂️

Exploratory Data Analysis (EDA) was pivotal in uncovering insights from my dataset. EDA involved:

- Analyzing order statuses, such as 'Delivered', 'Cancelled', and 'In Transit' to understand the order processing workflow.
- Evaluating the performance of different product categories.
- Exploring geographical insights, identifying regions with the highest order volumes.
- Investigating time series trends and seasonality.
- Assessing the impact of product styles on sales performance.
- Detecting and analyzing outliers for exceptional sales events.

My analysis aimed to extract actionable insights that drive future decision-making.

## Data Visualization 📊

The analysis results are presented through a variety of visualizations, making it more accessible and insightful. My data visualization steps included:

- Countplots to illustrate categorical attribute distributions.
- Bar charts to visualize sales amounts by categories and styles.
- Pie charts representing the distribution of categorical data.
- Boxplots revealing data distributions and outliers.
- Time series plots highlighting sales trends over time.
- Horizontal bar charts showcasing geographical sales distribution.

By transforming data into visual representations, I communicated insights effectively.

## Conclusion 📝

In conclusion, this data analysis project offers valuable insights into sales data from the e-commerce platform. 
The analysis covers various aspects, including order statuses, fulfilment categories, ship cities, and order amounts. 
The provided visualizations enhance the understanding of the data and can guide decision-making and strategy development for the e-commerce platform.
Feel free to explore my analysis.

Thank you for joining me on this data-driven journey! 🚀
