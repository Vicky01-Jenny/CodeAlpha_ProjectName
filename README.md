# CodeAlpha_ProjectName
README for Iris Dataset EDA project
Task 2 : Exploratory Data Analysis (EDA) on the Iris Dataset
Project Overview
This project performs an Exploratory Data Analysis (EDA) on the classic Iris Dataset, one of the most well-known datasets in data science and machine learning.  
The goal is to explore, visualize, and understand relationships among flower measurements (sepal and petal lengths and widths) across three Iris species Setosa, Versicolor, and Virginica.

Through this analysis, we uncover hidden patterns, correlations, and distinctions among the species, laying the groundwork for future machine learning tasks such as classification.

 Objectives
- Load and inspect the Iris dataset structure  
- Handle missing or inconsistent data  
- Analyze statistical summaries and feature distributions  
- Visualize data using plots to identify trends and relationships  
- Draw insights and interpret patterns between species  

Dataset Information
Dataset Name: Iris  
Source: [UCI Machine Learning Repository] (https://archive.ics.uci.edu/ml/datasets/iris)  
Number of Instances:150  
Number of Features: 4  
Features:
1. Sepal Length (cm)  
2. Sepal Width (cm)  
3. Petal Length (cm)  
4. Petal Width (cm)  
-Target Variable: Species (Setosa, Versicolor, Virginica)

Steps Performed

1. Data Loading & Overview
   - Loaded dataset using pandas
   - Displayed first few rows, column names, and data types

2. Data Cleaning
   - Checked for missing or null values
   - Ensured numeric data types for quantitative features

3. Statistical Summary
   - Used describe () for mean, standard deviation, and range
   - Identified patterns in petal and sepal dimensions

4. Data Visualization
   - Histograms for feature distributions  
   - Boxplots for outlier detection  
   - Pairplots to visualize feature relationships by species  
   - Heatmap for correlation analysis  
   - Violin plots for species-wise feature variation

5. Insights and Observations
   - Petal features show stronger separation between species  than sepal features  
   - Iris-setosa is clearly distinct from the other two species  
   - Sepal length and petal length are positively correlated  
   - No significant missing or duplicate values found  

Tools and Libraries Used
- Python
- Pandas – data handling  
- NumPy – numerical computations  
- Matplotlib – plotting and visualization  
- Seaborn – advanced statistical visualization  

 Findings
- EDA helps uncover important relationships within the data before modeling.  
- Visual patterns make Setosa easily separable, suggesting high classification accuracy.  
- This analysis builds a strong foundation for supervised learning tasks (e.g., logistic regression, SVM, decision trees).

Task 3: Dataset  on Sample Superstore for Data Visualization
Data Visualization on the Sample Superstore Dataset

Project Overview
This project explores the Sample Superstore Dataset using data visualization to uncover valuable business insights.  
The dataset contains detailed sales, profit, and customer information for a retail store operating across different North America regions.  

Through this analysis, I aim to identify:
- Sales and profit trends across regions, categories, and segments  
- Areas of potential profit loss  
- Key factors influencing business performance  

The project combines data cleaning, analysis, and visualization using tools like Tableau, Matplotlib, and Seaborn to communicate insights effectively.


 Objectives
- Analyze the sales and profit performance of the superstore  
- Visualize key business metrics across regions, states, and product categories  
- Identify underperforming areas and opportunities for growth  
- Craft an interactive Tableau Dashboard to communicate insights clearly to stakeholders  

Dataset Information
Dataset Name: Sample Superstore  
Source: [Tableau Public Sample Data](https://community.tableau.com/s/sample-superstore-data-set)  
Format: Excel (SampleSuperstore.xls)  
Number of Records: ~10,000  
Main Columns:
| Feature | Description |
| Order ID | Unique identifier for each order |
| Order Date | Date when the order was placed |
| Ship Mode | Shipping method used |
| Customer Name | Name of the customer |
| Segment | Market segment (Consumer, Corporate, Home Office) |
| Country, State, Region | Geographic details |
| Category, Sub-Category | Product categories |
| Sales | Sales revenue |
| Quantity | Number of items sold |
| Discount | Discount offered |
| Profit | Profit earned from the sale |

Steps Performed

1. Data Cleaning
- Removed duplicates and verified missing values  
- Converted date columns to proper datetime format  
- Checked for incorrect data entries or anomalies  

2. Exploratory Analysis
- Calculated total sales, total profit, and average discount  
- Grouped data by region, category, and customer segment  
- Identified profit contribution by sub-category  

3. Data Visualization
Created various charts and dashboards using Tableau and Python to represent insights:
- Sales vs. Profit Scatter Plot – to see correlation between revenue and profit  
- Bar Chart– for sales and profit by category and sub-category  
- Heatmap – for profit contribution across states  
- Line Charts – to observe monthly trends in sales and profit  

 4. Storytelling in Tableau
Developed a Tableau Story to communicate insights sequentially:
1. Executive Overview: KPIs like Total Sales, Profit, and Quantity Sold  
2. Regional Analysis:  Sales and profit by region and state  
3. Category Performance: Identification of best- and worst-performing categories  
4. Segment Insights: Comparison between Consumer, Corporate, and Home Office  
5. Profitability Dashboard: Detecting products with high discounts but low profits  

Key Insights
- West Region contributes the highest profit margin.  
- Technology category generates the highest sales, while Furniture often yields lower profit margins.  
- High discounts in the significantly reduce profit.  
- California and New York are top-performing states, while Texas and Pennsylvania show lower profitability.  
- The Consumer Segment drives most of the revenue, followed by Corporate.  

Tools and Technologies Used
- Tableau Desktop – Data dashboards and storytelling  
- Excel – Dataset storage and preparation  
- Python – Data exploration and validation using Pandas, Seaborn, Matplotlib  

Author
Victor Chukwuma Nwabufo 
nwabufovictor12@gmail.com

