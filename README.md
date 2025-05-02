##  Adidas U.S. Sales Data Analysis

---

This repository presents an end-to-end exploratory data analysis (EDA) of Adidas U.S. Sales Data using Python. The dataset captures detailed sales transactions, including information on retailers, products, customer demographics, financial performance, and sales timelines.

---

###  Dataset Description

The dataset used in this project (`AdidasSalesData.csv`) includes retail sales transaction records from Adidas. Each row represents a **single sales transaction**, making it ideal for sales trend analysis, profitability tracking, and regional performance evaluation.

####  Features Overview

| Feature Name       | Data Type | Description |
|--------------------|-----------|-------------|
| Retailer           | object    | Name of the retailer |
| Retailer Id        | int64     | Unique numeric ID for each retailer |
| Invoice Date       | datetime  | Date of transaction |
| Region             | object    | Sales region |
| State              | object    | U.S. state |
| City               | object    | City where the sale happened |
| Gender Type        | object    | Gender category of the product's target audience |
| Product Category   | object    | Product name |
| Price Per Unit     | float64   | Unit price of the product |
| Units Sold         | int64     | Number of units sold |
| Total Sales        | float64   | Total sales amount |
| Operating Profit   | float64   | Profit made on the transaction |
| Operating Margin   | float64   | Ratio of operating profit to total sales |
| Sales Method       | object    | Channel through which sales occurred |

---

### Technologies Used

- **Python 3.9+**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib & Seaborn** – data visualization
- **Power BI** – interactive dashboard
- **Jupyter Notebook** – interactive analysis

---

### Key Analyses Performed

- Data cleaning and type conversion
- Descriptive statistics
- Total sales and profit trends over time
- Regional and state-wise performance analysis
- Top-performing products and retailers
- Correlation between sales, profit, and other features
- Visual storytelling using Matplotlib and Power BI

---

### Key Time Series Visualizations

![3b868ac1-42ad-48e4-90af-b7c0e4a89500](https://github.com/user-attachments/assets/da3f3020-d188-43f2-9d02-9789f2e4fd77)

- **Total Sales Over Time**: Seasonal peaks and regional variation observed.
- **Profit Over Time**: Indicates consistent growth and higher margins in specific quarters.

---

### Power BI Dashboard

 File: `Adidas_Sales_Dashboard.pbix`  
A fully interactive dashboard created in Power BI summarizes key business metrics, including:

- Monthly sales trends  
- Retailer-wise performance  
- Product category breakdown  
- Sales method comparison  

>  To view the dashboard, open the `.pbix` file using [Power BI Desktop](https://powerbi.microsoft.com/desktop/).

![a29e1121-5cbb-4c96-8b6a-3b8af687c7b3](https://github.com/user-attachments/assets/6d9c1b4a-bbe6-4012-bd68-2072d0f4ab6a)


---

### Summary of Insights Gained

- Street Footwear is the best-selling and most profitable product category, followed by Apparel.
- Athletic Footwear has slightly lower sales but maintains strong margins.
- West Gear and Foot Locker lead in total sales and profits; Sports Direct has the highest operating margin (44.5%).
- West region dominates sales; Midwest region lags behind.
- July, August, and December show sales peaks; March is consistently weak.
- Overall growth in sales and profit from 2020 to 2021.
- Men dominate Street Footwear sales; women dominate Apparel.
- Charleston, New York, and Miami are the most profitable cities.
- Online sales yield the highest operating margin (46.4%) despite lower revenue.
- Outlet sales outperform in-store sales in both revenue and margin.
- Units Sold and Total Sales are highly correlated (0.91); both drive profit.
- Total Sales and Operating Profit have a very strong positive correlation (0.96).
- Price per Unit has a moderate positive correlation with profit.
- Operating Margin tends to decline with high-volume discounting.
- Apparel shows high profitability potential with consistent pricing.
- Dynamic pricing can optimize sales and margins, especially in Footwear.
- Some retailers show pricing patterns negatively correlated with Retailer ID.

---

### Business Recommendations

- Expand **Street Footwear** and **Apparel** lines with exclusive collections.
- Boost marketing efforts in the **Midwest** and improve **online visibility**.
- Launch seasonal campaigns in **July, August, and December**; incentivize March with promotions.
- Leverage **high online margins** by improving UX, delivery, and ads.
- Implement **dynamic pricing** in Footwear to optimize revenue.
- Increase **Outlet presence** in profitable states and cities.
- Personalize product development: men’s Street Footwear, women’s Apparel.
- Expand in high-performing cities: **Charleston**, **New York**, and **Miami**.
- Focus on **high-margin, higher-priced** items to increase profits.
- Use regional data to customize category-specific marketing strategies.

---

## Author

**Ashish Raj**  
[GitHub](https://github.com/AshishRaj97) | [LinkedIn](https://in.linkedin.com/in/ashish-raj-327596306)
