# Diwali Sales Data Analysis

This project provides a detailed analysis of Diwali sales data to understand trends and patterns in customer behavior, product sales, and other key factors that influence purchasing decisions during the Diwali festival.

## Dataset Information

The dataset consists of 11251 entries and 15 columns. Each entry represents a sale, and the columns contain information such as customer details, product information, order quantity, sales amount, and more.

### Columns in the Dataset:
- `User_ID`: Unique identifier for the user.
- `Cust_name`: Name of the customer.
- `Product_ID`: Unique identifier for the product.
- `Gender`: Gender of the customer (Male/Female).
- `Age Group`: Age group category of the customer.
- `Age`: Actual age of the customer.
- `Shaadi`: Marital status (0 = Not Married, 1 = Married).
- `State`: State where the customer resides.
- `Zone`: Geographical zone (Northern, Southern, Eastern, Western).
- `Occupation`: Occupation of the customer.
- `Product_Category`: Category of the purchased product.
- `Orders`: Number of orders placed by the customer.
- `Amount`: Total purchase amount for the customer.
- `Status`: (Removed due to null values)
- `unnamed1`: (Removed due to null values)

## Libraries Used

- `numpy` for numerical operations.
- `pandas` for data manipulation and analysis.
- `matplotlib` for data visualization.
- `seaborn` for statistical data visualization.

## Data Preprocessing

- The dataset is cleaned by dropping unnecessary columns (`Status`, `unnamed1`).
- Null values in the `Amount` column were dropped.
- Data types of certain columns (like `Amount`) were converted for consistency.
- The `Marital_Status` column was renamed to `Shaadi` for better clarity.

## Exploratory Data Analysis (EDA)

### Gender Distribution

- **Gender Count**: The majority of the customers are female, and females have higher purchasing power.
- **Total Amount by Gender**: Females contribute more to the total sales than males.

### Age Group Analysis

- **Age Group vs Gender**: Most buyers belong to the 26-35 age group, especially females.
- **Total Amount by Age Group**: The highest sales are from the 26-35 age group.

### State Analysis

- **Top 10 States by Orders**: Uttar Pradesh, Maharashtra, and Karnataka have the most orders.
- **Top 10 States by Sales Amount**: Uttar Pradesh, Maharashtra, and Karnataka also contribute the most in terms of sales amount.

### Marital Status

- **Marital Status Distribution**: Most buyers are married, and married women have higher purchasing power.

### Occupation Analysis

- **Occupation Distribution**: The majority of buyers work in the IT, Healthcare, and Aviation sectors.
- **Total Sales by Occupation**: The highest sales come from people working in IT, Healthcare, and Aviation.

### Product Category

- **Top 10 Product Categories by Sales**: The most popular product categories are Food, Clothing, and Electronics.
- **Top 10 Most Sold Products**: The products in the Food, Clothing, and Electronics categories are the most frequently purchased.

## Visualizations

### Gender vs Sales
- A bar chart showing the total sales by gender.
  
### Age Group vs Sales
- A bar chart showing the total sales by age group.

### State vs Orders and Sales
- Two bar charts: one showing the total number of orders by state, and the other showing the total sales by state.

### Marital Status vs Sales
- A bar chart comparing the total sales based on marital status and gender.

### Occupation vs Sales
- A bar chart comparing the total sales by occupation.

### Product Category vs Sales
- A bar chart showing the total sales for each product category.

### Top Products by Orders
- A bar chart showing the top 10 most sold products.

## Conclusion

From the analysis, we observe the following insights:
- The majority of buyers are females in the 26-35 age group.
- Uttar Pradesh, Maharashtra, and Karnataka are the key contributors to both orders and total sales.
- Married women exhibit the highest purchasing power.
- IT, Healthcare, and Aviation sector employees are the top buyers.
- Food, Clothing, and Electronics are the most sold product categories during the Diwali festival.

## License

This project is open-source and available under the MIT License.

---

Feel free to modify the analysis and visualizations according to your needs.

