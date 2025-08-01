# 🍔 Swiggy Data Analysis Project
-------------------------------------------------------------
This project involves analyzing and cleaning the dataset provided by Swiggy. Swiggy is a popular food delivery service in India, and the dataset includes various tables related to food items, menus, orders, order types, restaurants, and users. The goal is to clean the data, format the tables, and store the processed dataset for further analysis.
## Power BI Report
- [View the Power BI report here](https://app.powerbi.com/view?r=eyJrIjoiMzZiNzhkODUtNWZjZi00N2NjLWIwYjEtOWI4Yzk5NzlhYjVlIiwidCI6ImZmYzMxNjU1LTI0NTMtNGMzNy1iNmM3LWI4MzQ2ODM4MTc3NiJ9)

## 📊 Tables and Column Names

### 🍲 Food Table
- Column Names: `f_id`, `item`, `veg_or_non_veg`

### 📋 Menu Table
- Column Names: `menu_id`, `r_id`, `f_id`, `Cuisine`, `price`

### 📝 Orders Table
- Column Names: `order_date`, `sales_qty`, `sales_amount`, `currencty`, `user_id`, `r_id`

### 🛍️ Orders Type Table
- Column Names: `order_id`, `type`

### 🍴 Restaurant Table
- Column Names: `id`, `name`, `country`, `city`, `rating`, `rating_count`, `cuisine`, `link`, `address`

### 👥 Users Table
- Column Names: `user_id`, `name`, `age`, `gender`, `marital_status`, `occupation`

## 📝 Agenda
1. **🧹 Data Cleaning**
   - Handle null values in all tables.
   - Re-analyze and ensure all null values are correctly handled.

2. **🛠️ Data Formatting**
   - Change column names to be more descriptive and suitable.
   - Drop unnecessary columns that do not contribute to the analysis.
   - Drop unnecessary tables that are not required for further analysis.

3. **💾 Store Processed Data**
   - Save the cleaned and formatted dataset into the system for further analysis and visualization.
3. **💾 Data Visualization**
   - Create various visualizations to uncover trends and insights.

## 📊 Data Overview
- The dataset consists of 5 tables: Food, Menu, Orders, Orders Type, Restaurant, and Users.
- The data includes information for 100,000 users.
- The Menu table has a row count of 5.2 million.

## 🧼 Data Cleaning Steps
- Identify and handle null values in each table.
- Ensure that no critical data is lost in the process.

## 🛠️ Data Formatting Steps
- Change column names to be more intuitive and user-friendly.
- Remove columns that are deemed unnecessary for the analysis.
- Remove tables that do not add value to the analysis.
## 📊 Power BI Steps
- Load the cleaned data into Power BI.
- Use Power Query to make necessary transformations such as merging tables and extracting date components.
- Establish relationships between tables using primary and foreign keys.
- Create various visualizations to uncover trends and insights.

## 💾 Storing Cleaned Data
- After cleaning and formatting, store the processed data back into the system for further use.
## 🔍 Insights
- Found useful insights such as vegetarian options leading to 122 million in sales, 7.2% higher than non-vegetarian; the top 10% of customers accounting for 80% of sales; and Tirupati city recording the highest order amount at 43 million.
