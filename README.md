# Amazon Sales Dashboard using Power BI

## Project Overview

This project demonstrates the creation of an interactive sales dashboard using Microsoft Power BI. The dashboard analyzes Amazon sales data and provides insights into sales performance, customer behavior, product categories, payment methods, and order status.

## Dataset

The project uses the following dataset:

- amazon_sales_data 2025.csv

The dataset contains:

- Order ID
- Date
- Product
- Category
- Customer Name
- Customer Location
- Payment Method
- Quantity
- Price
- Total Sales
- Status

## Tools Used

- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- CSV Dataset

## Dashboard Features

- Total Sales KPI
- Total Orders KPI
- Average Order Value KPI
- Sales Trend (Line Chart)
- Sales by Category (Bar Chart)
- Sales by Customer Location
- Payment Method Distribution
- Order Status Analysis
- Interactive Slicers (Date, Category, Location, Status)

## DAX Measures

```DAX
Sales Amount = SUM('amazon-sales'[Total Sales])

Total Orders = DISTINCTCOUNT('amazon-sales'[Order ID])

Average Order Value =
DIVIDE([Sales Amount], [Total Orders])
```

## How to Open the Project

1. Download the repository.
2. Open **Amazon Sales Dashboard.pbix** using Microsoft Power BI Desktop.
3. If prompted, reconnect the dataset.
4. Refresh the data.

## Project Structure

```
Amazon-Sales-PowerBI-Dashboard/
│
├── Amazon Sales Dashboard.pbix
├── amazon_sales_data 2025.csv
├── README.md
└── Screenshots/
```

## Author

**Name:** Your Name

**Course:** Business Intelligence / Data Analytics

**Year:** 2026

## License

This project is created for educational purposes.
