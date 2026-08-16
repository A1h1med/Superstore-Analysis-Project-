## Superstore Analysis Project

## Project Overview 
- This project aims to clean and analyze the Superstore dataset and visualize key business insights using Python, Pandas, and Matplotlib.
  
<img width="1672" height="941" alt="Overview 1" src="https://github.com/user-attachments/assets/cfc216fb-098a-4d2b-89ed-b81f6e328bd7" />


## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Numpy
- Jupyter Notebook
  
## Dataset Overview

The Superstore dataset contains information about sales, customers, products, and orders.
The dataset contains 9,994 rows and 21 columns

<img width="1793" height="291" alt="image" src="https://github.com/user-attachments/assets/6742a4e5-d910-47e0-aa9a-539e1fc6fb73" />


It includes key attributes such as:

- Order Date
- Customer Information
- Product Information
- Category and Sub-Category
- Sales
- Quantity
- Discount
- Profit
- Shipping Information

The dataset is used to analyze sales performance and identify key business insights through data cleaning, exploratory data analysis, and visualization.

## Data Cleaning

<img width="597" height="89" alt="image" src="https://github.com/user-attachments/assets/630c2131-0dfc-4397-b9b9-2170008d6975" />


The dataset was cleaned and prepared for analysis by performing the following steps:

- Handling missing values using (mean/median) or mode 
- Removing duplicate records
- Correcting data types
- Handling inconsistent values
- Checking for outliers
- Standardizing text values
- Preparing the data for analysis and visualization

## Exploratory Data Analysis (EDA)

After cleaning the dataset, exploratory data analysis was performed to understand the main patterns and characteristics of the data.

The analysis focused on:

- Analyzing sales and profit performance
- Examining product and category performance
- Identifying top-performing products
- Analyzing sales trends over time

## Data Visualization

Matplotlib was used to visualize the key patterns and trends identified during the exploratory data analysis.

The visualizations include:

- Sales over months for each year
  
- <img width="1023" height="662" alt="image" src="https://github.com/user-attachments/assets/d61029ab-3391-412c-90d0-729c8a27dd63" />

  Q1) Why the last quarter always have high sales? 🔎
  
  <img width="958" height="584" alt="image" src="https://github.com/user-attachments/assets/b6e77846-a193-4e72-b473-7587d900029b" />

  Insights 📌:  It can depend on two factors: discounts and new product releases.
  ## ----------------------------------------------------------------------------------
- Sales over years
  
  <img width="483" height="504" alt="image" src="https://github.com/user-attachments/assets/d4815382-c16f-496d-8165-8ce1958ce880" />
  
  َQ2) How have sales changed over the years? 🔎
  
  Insights 📌: Sales showed a steady upward trend over the years, peaking in 2019.
  ## ----------------------------------------------------------------------------------
- Top 5 products by profit

  <img width="1141" height="438" alt="image" src="https://github.com/user-attachments/assets/fd829230-8633-40ea-9b58-6034f4788f3d" />
  
  Q3) Which product generates the highest profit? 🔎
  
  Insights 📌: Canon Image Class 2200 generates the highest profit among all products 
  ## ----------------------------------------------------------------------------------
- Profit by Category

  <img width="510" height="503" alt="image" src="https://github.com/user-attachments/assets/88508342-171e-4885-91e3-372e665d94a5" />
  
  Q4) Which category is the most profitable? 🔎
  
  Insights 📌: Technology is our most profitable category
  ## ----------------------------------------------------------------------------------
- Top 5 cities by number of orders
  
  <img width="851" height="586" alt="image" src="https://github.com/user-attachments/assets/2de5e0ab-b1ed-4765-a507-af888bdae74a" />
  
    Q5) Which city has the highest sales? 🔎
  
    Insights 📌: We reached our peak in sales in New York City  
