# Exploratory Data Analysis on Sales Transactions

## Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on sales transactions data to gain actionable insights about customer behavior, product categories, and sales patterns. The analysis includes transaction counts, sales amounts, age groups, gender distributions, top states, product categories, and professions.

## Dataset
The dataset `Sales_Data.csv` contains sales transaction records with the following columns:

- **Customer_ID**: Unique identifier for each customer  
- **Gender**: Customer gender (Male/Female)  
- **Age**: Age of the customer  
- **Age Group**: Age range category  
- **State**: Customer location  
- **Profession**: Customer profession  
- **Product_Category**: Category of the purchased product  
- **Orders**: Number of products ordered  
- **Amount**: Total transaction amount  

## Objective
- Analyze **gender-wise** and **age-wise** transaction trends.  
- Identify **top performing states** by order count and sales amount.  
- Explore **product categories** and **professions** that contribute most to sales.  
- Generate visual insights to support decision-making.

## Key Insights
- Females aged **26-35** from **Uttar Pradesh, Maharashtra, and Karnataka**, working in **IT, Healthcare, and Aviation**, are more likely to purchase products from the **Beauty, Sports, and Electronics** categories.  
- Gender, age group, state, product category, and profession strongly influence transaction patterns and sales amounts.

## Visualizations
1. **Gender-wise transaction count** – Bar Chart & Pie Chart  
2. **Gender-wise total sales amount** – Bar Chart  
3. **Age Group-wise transaction count & total sales** – Bar Chart  
4. **Top 5 States by orders & sales amount** – Bar Chart  
5. **Product Category-wise transactions & total sales** – Bar Chart  
6. **Product Category & Gender-wise transactions** – Grouped Bar Chart  
7. **Profession-wise transactions & top 3 professions by sales** – Bar Chart  

## Sample Visualizations

### Gender-wise Transaction Count
![Gender-wise Transaction Count]([images/gender_transactions.png](https://github.com/Kashyapdhimmar/Sales-Transactions-EDA/blob/2968760defb626404c190b1f5c1cd921a88688b2/Gender-wise%20Transaction%20Count.png))

### Age Group-wise Total Sales
![Age Group-wise Sales]([images/agegroup_sales.png](https://github.com/Kashyapdhimmar/Sales-Transactions-EDA/blob/2968760defb626404c190b1f5c1cd921a88688b2/Age%20Group-wise%20Sales.png))

## How to Run
1. Ensure you have Python 3.x installed.
2. Open `EDA_Sales_Transactions.ipynb` in Jupyter Notebook or VS Code.
3. Run each cell sequentially to replicate the analysis.

## Files
- `Sales_Data.csv` – Sales transactions dataset
- `EDA_Sales_Transactions.ipynb` – Jupyter Notebook containing the full analysis
- `README.md` – Project overview and instructions

## Technologies Used
- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
