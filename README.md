# Task-4-Dashboard-Design

# Task 4 - Dashboard Design using Power BI

## Objective

The objective of this project is to design an interactive dashboard for business stakeholders using Power BI. The dashboard provides insights into sales performance, profitability, and business trends through KPIs and visualizations.

## Tools Used

* Power BI Desktop
* Microsoft Excel
* DAX (Data Analysis Expressions)
* GitHub

## Dataset

Financial Sample Dataset

## DAX Measures (KPIs)

### Total Sales

```DAX
Total Sales = SUM('Data'[ Sales])
```

### Total Profit

```DAX
Total Profit = SUM('Data'[Profit])
```

### Total Units Sold

```DAX
Total Units Sold = SUM('Data'[Units Sold])
```

### Profit Margin %

```DAX
Profit Margin % =
DIVIDE([Total Profit],[Total Sales],0)*100
```

### Sales Growth %

```DAX
Sales Growth % =
VAR PreviousSales =
    CALCULATE(
        [Total Sales],
        DATEADD('Data'[Date],-1,MONTH)
    )
RETURN
    DIVIDE([Total Sales]-PreviousSales,PreviousSales,0)*100
```

## Dashboard Visualizations

### KPI Cards

* Total Sales
* Total Profit
* Total Units Sold
* Profit Margin %

### Charts

* Sales Trend Analysis (Line Chart)
* Sales by Product (Bar Chart)
* Profit by Country (Column Chart)
* Sales by Segment (Donut Chart)

### Slicers

* Country
* Product
* Segment
* Year

## Key Insights

* Sales performance differs across products and countries.
* Some products generate higher profits than others.
* Profit Margin helps evaluate overall business efficiency.
* Sales trends reveal growth patterns over time.
* Interactive filters allow detailed analysis of business performance.

## Dashboard Features

* Interactive KPI Cards
* Dynamic Filtering with Slicers
* Time-Series Analysis
* Business Performance Monitoring
* User-Friendly Dashboard Layout

## Project Outcome

This dashboard enables stakeholders to monitor business performance, identify trends, and make data-driven decisions using interactive visualizations.

## Repository Contents

* Financial Sample Data.xlsx
* Dashboard.pbix
* Dashboard Screenshot.png
* Dashboard Summary PPT.pptx
* README.md

## Author

Balagonda Manjunatha

