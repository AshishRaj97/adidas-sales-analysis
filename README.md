# Adidas U.S. Sales Analysis

An exploratory analysis of Adidas U.S. sales data using Python and Power BI. The project examines sales and operating-profit patterns across retailers, products, regions, and sales channels, then translates the findings into questions a business team could investigate.

## Business questions

- Which product categories and retailers contribute the most sales and operating profit?
- How do sales vary by region and over time?
- How do online, outlet, and in-store channels compare?
- Which patterns may warrant further investigation by a commercial team?

## Dataset

The dataset, AdidasSalesData.csv, contains transaction-level records with fields including:

| Field | Description |
|---|---|
| Retailer / Retailer ID | Retailer name and identifier |
| Invoice Date | Transaction date |
| Region / State / City | Geographic attributes |
| Gender Type | Target-audience category |
| Product Category | Product category |
| Price Per Unit | Unit price |
| Units Sold | Quantity sold |
| Total Sales | Transaction sales amount |
| Operating Profit | Recorded operating profit |
| Operating Margin | Recorded operating margin |
| Sales Method | Online, outlet, or in-store channel |

## Tools

- Python 3.9+
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook
- Power BI

## Analysis performed

The notebook and dashboard cover data inspection, cleaning, and type conversion; descriptive statistics and sales trends over time; product, retailer, regional, and city-level comparisons; operating-profit and operating-margin analysis; relationships between numerical sales variables; and interactive Power BI views for monthly trends, retailer performance, product categories, and sales methods.

## Selected findings from the analysis

The original analysis reported the following patterns:

- Street Footwear and Apparel were among the leading categories by sales and profitability.
- West Gear and Foot Locker were among the leading retailers by sales and profit.
- The West region led total sales in the analyzed dataset.
- July, August, and December showed seasonal sales peaks.
- Online sales had a higher recorded operating margin than some other channels, despite lower revenue.

These are descriptive findings from this dataset, not causal conclusions or forecasts. They should be rechecked against the source data and dashboard filters before being used for business decisions.

## Visuals

**Sales and profit trends**

![Sales and profit trends](https://github.com/user-attachments/assets/da3f3020-d188-43f2-9d02-9789f2e4fd77)

**Power BI dashboard**

The repository includes Adidas_Sales_Dashboard.pbix. Open it with [Power BI Desktop](https://powerbi.microsoft.com/desktop/).

![Power BI dashboard](https://github.com/user-attachments/assets/6d9c1b4a-bbe6-4012-bd68-2072d0f4ab6a)

## Run the analysis

~~~bash
git clone https://github.com/AshishRaj97/adidas-sales-analysis.git
cd adidas-sales-analysis
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook
~~~

Open the analysis notebook and ensure the CSV path matches your local copy of the dataset. To inspect the dashboard, open the PBIX file in Power BI Desktop.

## Business considerations

The analysis suggests possible areas for further investigation, including channel-level margin differences, regional performance, and seasonal demand. Before making pricing, inventory, or marketing decisions, a business team should validate these patterns with current data and account for costs, promotions, and other relevant factors.

## Author

**Ashish Raj** · [GitHub](https://github.com/AshishRaj97) · [LinkedIn](https://www.linkedin.com/in/ashish-raj-327596306/)
