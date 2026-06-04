# Task-4-Dashboard-Design
Objective

The objective of this task is to design an interactive business dashboard using Power BI to analyze sales and financial performance. The dashboard helps stakeholders monitor key metrics, identify trends, and make data-driven decisions.

Tools Used
Power BI Desktop
Microsoft Excel
GitHub
Dataset

Financial Sample Dataset (Excel)

KPIs Created

The following Key Performance Indicators (KPIs) were created using DAX measures:

Total Sales = SUM('Data'[ Sales])

Total Profit = SUM('Data'[Profit])

Total Units Sold = SUM('Data'[Units Sold])

Profit Margin % =
DIVIDE([Total Profit],[Total Sales],0)*100
Dashboard Components
KPI Cards
Total Sales
Total Profit
Total Units Sold
Profit Margin %
Visualizations
Sales Trend Analysis (Line Chart)
Sales by Product (Bar Chart)
Profit by Country (Column Chart)
Sales by Segment (Donut Chart)
Slicers
Country
Product
Segment
Year
Key Insights
Sales performance varies across different products and countries.
Certain products contribute significantly to total revenue.
Profit margins provide insight into business profitability.
Sales trends help identify periods of growth and decline.
Interactive filters allow users to analyze specific segments and regions.
Dashboard Features
Interactive KPI Cards
Dynamic Filtering using Slicers
Time-Series Analysis
Business Performance Monitoring
Clean and Consistent Dashboard Design
Outcome

This project demonstrates how Power BI can be used to create interactive dashboards that provide meaningful business insights through data visualization and KPI tracking.

Repository Structure
Task-4-Dashboard-Design
│
├── Dataset
│   └── Financial Sample Data.xlsx
│
├── Dashboard
│   └── Dashboard.pbix
│
├── Screenshots
│   └── Dashboard.png
│
├── PPT
│   └── Dashboard_Summary.pptx
│
└── README.md
Author

Balagonda Manjunath
