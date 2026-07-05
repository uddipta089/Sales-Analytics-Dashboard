# Sales-Analytics-Dashboard

### Dashboard Link : <https://app.powerbi.com/groups/517527f9-8e51-484a-897f-4d7038a8614e/reports/c699e142-b145-4653-880c-63b82e204ff0/7c9529d3890e651ce5ce?experience=power-bi>

# Problem Statement

This dashboard helps businesses analyze sales performance, pricing trends, and regional market insights. It enables users to monitor sales growth, compare offer and purchase prices, evaluate regional performance, and identify key factors influencing property prices.

Using interactive dashboards, stakeholders can explore housing market trends across different regions, house types, and sales categories. The dashboard also provides Year-over-Year (YoY) Sales Growth, Last 12 Month Sales, Average Price per SQM, Median Sales Price Change, and property-specific pricing analysis to support data-driven decision-making.

Interactive filters allow users to drill down into specific regions, cities, sales types, and property categories for detailed business analysis.

---

## Steps Followed

- Step 1 : Connected the MySQL database to Power BI Desktop using the MySQL connector.

- Step 2 : Imported the housing sales dataset into Power BI Desktop.

- Step 3 : Opened Power Query Editor and enabled **Column Quality**, **Column Distribution**, and **Column Profile** to validate the dataset.

- Step 4 : Performed data cleaning and transformation using Power Query Editor by correcting data types, removing unnecessary columns, and preparing the dataset for analysis.

- Step 5 : Created the required relationships between tables to build the data model.

- Step 6 : Designed the report theme and page layouts for better visualization.

- Step 7 : Added slicers for the following fields:

  (a) Area

  (b) City

  (c) Sales Type

  (d) Region

- Step 8 : Created DAX measures for:

  (a) Year-over-Year (YoY) Sales Growth

  (b) Last 12 Month Sales

  (c) Median Sales Price Change

  (d) Units Sold

  (e) Offer Price vs Purchase Price

- Step 9 : Created KPI cards to display:

  - Latest Units Sold

  - Last 12 Month Sales

- Step 10 : Built the **House Market Overview** dashboard containing:

  - YoY Sales Growth by Sales Type

  - Offer Price vs Purchase Price

  - Median Sales Price Change by Region

  - Latest Units Sold

  - Last 12 Month Sales

- Step 11 : Developed the **Sales Performance** dashboard consisting of:

  - Sales by Region

  - Average Price per SQM by Region

  - Offer to SQM Ratio by Sales Type

  - Sales Transaction Table

  - Key Influencers Visual

- Step 12 : Built the **House Type Analysis** dashboard to compare:

  - Average Offer Price vs Purchase Price

  - Average SQM

  - SQM Price

  - Inflation

  - Interest Rate

  - Yield

across different property types.

- Step 13 : Used the **Key Influencers** visual to identify factors affecting Purchase Price.

- Step 14 : Added interactive filtering across all report pages using Area, City, Region, and Sales Type slicers.

- Step 15 : Published the report to Power BI Service.

---

# Snapshot of Dashboard (Power BI Service)

<img width="1911" height="906" alt="Screenshot 2026-07-05 205723" src="https://github.com/user-attachments/assets/e641699e-31d2-4cbe-ba05-3e1c2d4637a0" />



---

# Report Snapshot (Power BI Desktop)

## House Market Overview

<img width="1732" height="793" alt="Screenshot 2026-07-05 213108" src="https://github.com/user-attachments/assets/a12216bc-25eb-4a27-9aee-f1fda3e9969b" />



---

## Sales Performance

<img width="1731" height="792" alt="Screenshot 2026-07-05 213052" src="https://github.com/user-attachments/assets/0dd36d2e-ce64-4894-af49-5548532ba9df" />





---

## House Type Analysis

<img width="1741" height="790" alt="Screenshot 2026-07-05 213034" src="https://github.com/user-attachments/assets/1ee93d53-4c0d-40d1-943c-1e0ab023ebe6" />



---

# Report PDF

If you don't have Power BI Desktop installed, you can view the complete dashboard report in PDF format.

📄 **Sales Analytics Dashboard Report**

[Download the Report PDF](https://github.com/user-attachments/files/29676646/SalesAnalytics.pdf)

---
# Insights

A three-page interactive report was created in Power BI Desktop and published to Power BI Service.

Following inferences can be drawn from the dashboard;

## [1] House Market Overview

### Year-over-Year (YoY) Sales Growth

- Sales growth was analyzed across different sales categories:
  - Auction
  - Regular Sale
  - Family Sale
  - Other Sale

The YoY Sales Growth visual enables comparison of annual sales performance across various sales types and helps identify market trends.

---

### Offer Price vs Purchase Price

The dashboard compares Offer Price with Purchase Price, allowing users to evaluate pricing differences and negotiation trends in the housing market.

This visual changes dynamically based on the selected filters.

---

### Median Sales Price Change

Median Sales Price Change was analyzed across different regions including:

- Zealand
- Jutland
- Fyn & Islands
- Bornholm

This helps identify regions experiencing positive or negative price movement over time.

---

### KPI Cards

The dashboard displays:

- Latest Units Sold
- Last 12 Month Sales

These KPIs provide a quick overview of current market performance.

---

## [2] Sales Performance

The Sales Performance page provides detailed regional sales analysis.

### Sales by Region

Sales distribution is analyzed across:

- Zealand
- Jutland
- Fyn & Islands
- Bornholm

allowing users to compare market performance across different regions.

---

### Average Price per SQM

Average property price per square meter is compared across regions, enabling better understanding of regional pricing differences.

---

### Offer to SQM Ratio

The dashboard compares Offer to SQM Ratio for:

- Regular Sale
- Other Sale
- Family Sale
- Auction

This helps evaluate pricing efficiency across different sales categories.

---

### Key Influencers

The Key Influencers visual identifies important factors affecting Purchase Price.

Users can explore which variables contribute most significantly to increases or decreases in property prices.

---

## [3] House Type Analysis

This page compares various housing categories including:

- Farm
- Apartment
- Villa
- Townhouse
- Summerhouse

The dashboard analyzes:

- Average Offer Price
- Average Purchase Price
- Average SQM
- Average SQM Price
- Inflation
- Interest Rate
- Yield

allowing users to compare property performance across different house types.

---

## [4] Interactive Filtering

Interactive slicers allow users to filter the dashboard by:

- Area
- City
- Region
- Sales Type

All visuals update dynamically based on the selected filters, enabling detailed business analysis.

---

## [5] Business Insights

Using this dashboard, decision-makers can:

- Monitor Year-over-Year sales performance.
- Compare Offer Price with Purchase Price.
- Identify high-performing regions.
- Analyze pricing trends across house types.
- Evaluate regional differences in property values.
- Discover factors influencing Purchase Price through Key Influencers.
- Explore housing market trends using interactive visualizations.

The dashboard provides a comprehensive view of sales performance and market behavior, supporting data-driven business decisions.

# Dashboard Features

The dashboard includes the following interactive features:

- Dynamic slicers for Area, City, Region, and Sales Type.
- Cross-filtering and cross-highlighting between visuals.
- Interactive KPI cards displaying key business metrics.
- Regional sales analysis using bar and column charts.
- Pricing comparison using scatter and comparison charts.
- Key Influencers visual to identify factors affecting Purchase Price.
- Drill-down capability through Year, Quarter, Month, and Day hierarchy.
- Responsive report pages for better user experience.

---

# Business Value

This dashboard helps organizations to:

- Monitor overall sales performance.
- Analyze regional market trends.
- Compare Offer Price and Purchase Price.
- Track Year-over-Year sales growth.
- Identify high-performing regions.
- Understand pricing behavior across different house types.
- Support strategic decision-making through interactive visual analytics.

---

# Files Included

This repository contains:

- Sales Analytics Dashboard.pbix
- Sales Analytics Report.pdf
- Dataset
- README.md

---

# How to Use

1. Clone this repository.

```
git clone https://github.com/uddipta089/Sales-Analytics-Dashboard
```

2. Import the dataset into MySQL.

3. Open the Power BI (.pbix) file.

4. Update the MySQL connection if required.

5. Refresh the dataset.

6. Explore the interactive dashboards.

---

# Dashboard Link

Power BI Service

[Sales Analytics Dashboard](https://app.powerbi.com/groups/517527f9-8e51-484a-897f-4d7038a8614e/reports/c62aeb97-5dc2-4645-b74f-714b935b6464/7c9529d3890e651ce5ce?experience=power-bi)

---

# GitHub Repository

[Sales Analytics Dashboard](https://github.com/uddipta089/Sales-Analytics-Dashboard)

---

# Dataset

[Housing Data](https://github.com/user-attachments/files/29676439/Housing.Data.csv)

---

# Author

**Uddipta Pathak**

LinkedIn:
[Uddipta Pathak](https://www.linkedin.com/in/uddipta-pathak-144272335/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BxGYUjRMARu6n%2BFP6WvNvHA%3D%3D)

GitHub:
[uddipta089](https://github.com/uddipta089)

Email:
<uddiptapathak0831@gmail.com>

---

# Acknowledgements

This project was developed as part of my Data Analytics portfolio to demonstrate practical skills in:

- MySQL
- Power BI
- Power Query Editor
- DAX
- Data Modeling
- Business Intelligence
- Data Visualization

---

# Future Improvements

- Real-time MySQL database integration.
- Automated data refresh using Power BI Service.
- Sales forecasting using Machine Learning.
- Customer segmentation dashboard.
- Additional financial KPI dashboards.
- Mobile-optimized Power BI report.

---
