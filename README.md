# Power BI Business Intelligence: Sales & Operations Performance Dashboard

Power BI dashboard for analyzing **sales performance, customer segmentation, product profitability, and time intelligence**.

![image alt](https://github.com/Gulzaaat/Sales-and-Product-data/blob/a85f3c9a8cecb67b747dbf50942c285f7e83a3fa/data0.jpg)
![image alt](https://github.com/Gulzaaat/Sales-and-Product-data/blob/3a751d8f4fe3943bd9841031d1a3d43259e65f30/data1.jpg)
![image alt](https://github.com/Gulzaaat/Sales-and-Product-data/blob/3a751d8f4fe3943bd9841031d1a3d43259e65f30/data2.jpg)
![image alt](https://github.com/Gulzaaat/Sales-and-Product-data/blob/3a751d8f4fe3943bd9841031d1a3d43259e65f30/data3.jpg)
## Features
- Sales vs Sales Plan KPIs  
- Customer and product analysis  
- Top customers and products  
- Monthly & YoY growth metrics  

## Tech stack
- Power BI Desktop  
- DAX (time intelligence, KPIs)  
- Star schema data model
- ![image alt](https://github.com/Gulzaaat/Sales-and-Product-data/blob/c99b28c9555e3337677b297f835ee6320cad3e05/schema.png)

## Skills demonstrated
- Data modeling  
- DAX calculations  
- Interactive dashboards

## Key insights:
- The dashboard provides a clear and detailed view of sales performance, customer behavior, and product profitability, which are crucial for strategic decision-making.
- Insights into top customers and top products help focus sales and marketing efforts on the most profitable segments.
- The time intelligence features enable the tracking of sales trends, helping businesses adjust strategies for growth and forecasting.
- Customer segmentation by age, segment, and region offers insights into which groups are driving sales, allowing businesses to tailor marketing efforts.
- By integrating year-over-year growth data, the dashboard offers a robust way to measure performance and project future growth potential.

### Data sources overview

The project is built on a diverse set of data sources (distributed across `.csv` and `.xlsx` formats) integrated into a unified data model. The dataset follows the classic **AdventureWorks** business scenario, simulating a global manufacturing and retail operation.

#### 1. Sales & Transactions (Fact Tables)

* **Sales_data.csv / Sales Order_data.csv**: These serve as the core fact tables containing granular transaction records. They include critical fields such as Order Numbers, Transaction Dates, Product/Customer IDs, Quantities, and Revenue metrics.
* **Reseller_data.csv**: Provides comprehensive data on B2B sales through intermediaries (resellers), enabling a comparative analysis between direct and indirect sales channels.

#### 2. Customer Intelligence (Dimension Tables)

* **Customer_data.xlsx / Updated_Customer_Data.xlsx**: These files house rich demographic information, including customer gender, income levels, education, and geographic distribution.
* **New_Customer_Data.xlsx**: Supplemental datasets for new customer acquisitions, which were consolidated with the master database during the ETL process to ensure a holistic view of the customer base.

#### 3. Product & Catalog (Dimension Tables)

* **Product_data.xlsx / Product_data-2.xlsx**: A detailed product catalog categorized by lines and sub-categories. This data was instrumental in conducting profitability analysis across different product segments.

#### 4. Strategic Planning (Reference Data)

* **SalesPlan.xlsx / SalesPlanNew.xlsx**: Contains strategic sales targets and quotas for the 2020 fiscal year and beyond. These files were vital for performing **Plan-vs-Actual (Variance) Analysis** using advanced DAX measures.

**Author:** Gulzat Duisenbek
