# DataAnalysis-PythonProject-BlinkitAnalysis
---

### Overview
Using some important Python modules this data Analysis project aims to provide insights into the sales performance of an e-commerce company over the past year.
finding key insights based on some valuable KPIs helps us to Analyse and Visualize the sales performance. 

Exploratory Data Analysis (EDA) is a important step in data analysis which focuses on understanding patterns, trends and relationships through statistical tools and visualizations. 
Python offers various libraries like pandas, numPy, matplotlib, seaborn and plotly which enables effective exploration and insights generation to help in further modeling and analysis.

---
### Data Sources
The Primary dataset used for the analysis is the ""BlinkIT Grocery Data.csv"" file containing detailed information of the company for our analysis process.

---
### Tools
Jupyter Notebook (Anaconda Navigator) for EDA and Visualization.

---
### Important Libraries/Python Modules
- matplotlib.pyplot
- pandas
- numpy
- seaborn

---
### KPI's for Analysis
To conduct a comprehensive analysis of Blinkit's sales performance, customer satisfaction, and inventory distribution 
to identify key insights and opportunities for optimization using various KPIs and visualizations in Python(jupyter notebook).

- KPI's Requirements(Key Performance Indicator)
  - Total Sales: The overall revenue generated from all items sold.
  - Average Sales: The average revenue per sale.
  - Number of Items: The total count of different items sold
  - Average Rating: The average customer rating for items sold.

- Chat's Requirements
  - Total Sales by Fat Content - (**Pie Plot**)
  <img width="711" height="533" alt="Fat_Content" src="https://github.com/user-attachments/assets/09f26a28-2e58-4f7d-a9de-2521d2b9d49a" />

  ---

  - Total Sales by Item Type - (**Bar Plot**)
  <img width="1327" height="732" alt="Item_Type" src="https://github.com/user-attachments/assets/764177af-e0d8-4506-b105-298fa727b5a9" />

  ---

  - Fat Content by Outlet for Total Sales - (**Stacked Bar Plot**)
  <img width="1052" height="610" alt="Item_fat_content" src="https://github.com/user-attachments/assets/3a792081-60b2-4a18-9e3d-0c57c3f258c3" />

  ---

  
  - Total Sales by Outlet Establishment - (**Line Plot**)
  <img width="1292" height="595" alt="Establishment" src="https://github.com/user-attachments/assets/b9ed6584-a126-4027-87bf-30639e1b3bd6" />

  ---

  - Sales by Outlet Size - (**Pie Plot**)
  <img width="498" height="484" alt="Outlet_Size" src="https://github.com/user-attachments/assets/ea15fea6-2749-41f3-b1d9-67a805455780" />

  ---

  - Sales by Outlet Location - (**Bar Plot**)
  <img width="916" height="372" alt="Location_type" src="https://github.com/user-attachments/assets/e7a91209-2762-4401-b826-023c53eb92e8" />

---
### Some Valuable Calculations for Analysis
- Total Sales-

  **total_sales = df['Total Sales'].sum()**

- Average Sales-

  **avg_sales = df['Total Sales'].mean(numeric_only = True)**

- No. of Items Sold-

  **Items_sold = df['Total Sales'].count()**

- Average Rating-

  **avg_rating = df['Rating'].mean(numeric_only = True)**

