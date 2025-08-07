# 📊 Task 3: Retail Sales Dashboard – Data Analyst Internship

## 🎯 Objective
Design an interactive dashboard in Power BI to help business stakeholders gain insights into sales, profit, and growth using a sales-financial dataset.

## 🧰 Tools Used
- Power BI Desktop
- Dataset from Kaggle

## 📂 Dataset Description
**Dataset:** Retail Sales Dataset (Kaggle)  
**Fields Used:** Transaction ID, Date, Customer ID, Gender, Age, Age Group (created), Category, Quantity, Price, Total (calculated)

## 🧹 Data Cleaning Steps (Power Query)
- Removed duplicates and nulls
- Formatted data types correctly (Date, Number, Text)
- Created a calculated `Total` column: `Quantity * Price`
- Created a new column `Age Group` based on age using conditional logic
- Handled missing values and outliers

## 🧮 DAX Measures Used
```DAX
Total Sales = SUM(retail_sales_dataset[Total])
Average Sales = AVERAGE(retail_sales_dataset[Total])
Total Quantity = SUM(retail_sales_dataset[Quantity])
Customer Count = DISTINCTCOUNT(retail_sales_dataset[Customer ID])
```

## 📊 Visualizations Created
- **KPI Cards**: Total Sales, Average Sales, Quantity, Customer Count
- **Line Chart**: Total Sales by Year (Time-Series Analysis)
- **Bar Chart**: Sales by Product Category
- **Stacked Column Chart**: Sales by Category and Gender
- **Donut Chart**: Sales and Customer Count by Age Group
- **Table**: Detailed Transaction Data (Date, Category, Quantity, Total, etc.)
- **Slicers/Filters**: Gender, Age Group, Category, Date

## 🎨 Design Features
- Applied consistent color theme from Power BI View tab
- Created navigation menu and interactive slicers
- Used cards for summary totals
- Organized visuals for clean, readable layout

## 📈 Key Insights
- Young Adults and Male customers contributed the most to overall sales
- Electronics and Clothing were the top-performing categories
- Sales increased steadily over time
- Certain customers contributed disproportionately high revenue
- Sales target progress tracked with KPI

## 🧠 Learning Outcomes
- Learned how to transform raw retail data into business insights
- Improved skills in Power BI, DAX, and dashboard design
- Practiced trend analysis and KPI development
- Enhanced data storytelling using interactive elements
# task-3
