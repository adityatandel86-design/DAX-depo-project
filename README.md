DAX Depo – Advanced DAX Calculations in Power BI

Project Overview

DAX Depo is a Power BI project focused on advanced DAX calculations, data modeling, KPI development, and analytical reporting. The project demonstrates how DAX functions can be used to generate meaningful business insights from Sales and Returns data without relying on traditional charts and dashboards.

---

Objective

The primary objective of this project is to build a robust Power BI data model and perform advanced calculations using DAX to analyze sales performance, profitability, returns, and time-based business metrics.

---

Dataset Tables

- Sales_Fact
- Returns_Fact
- Customer_Dim
- Product_Dim
- Date_Dim
- Region_Dim

---

Data Model

A star schema data model was created by establishing relationships between fact and dimension tables.

Model View

"Model View" (Images/model_view.png)

---

Calculated Columns

The following calculated columns were created:

Sales_Fact

- Profit = SalesAmount - Cost
- ReturnFlag = Returned / Not Returned

Customer_Dim

- Customer Full Name

Calculated Columns Preview

"Calculated Columns" (Images/calculated_columns.png)

---

DAX Measures

A dedicated Measure Table was created to organize all DAX measures.

Measures Created

- Total Sales
- Total Cost
- Total Profit
- Return Rate
- Average Sale per Transaction
- Year-over-Year Sales Growth
- Previous Month Sales Difference

Measure Table

"Measure Table" (Images/measure_table.png)

---

Matrix Visual Analysis

All analytical results were displayed using Matrix visuals grouped by:

- Region
- Month
- Product Category
- Customer Segment

Matrix Visual

"Matrix Visual" (Images/matrix_visual.png)

---

DAX Functions Used

Aggregation Functions

- SUM()
- AVERAGE()
- MAX()

Iterator Functions

- SUMX()
- AVERAGEX()
- COUNTX()

Logical Functions

- IF()
- AND()
- OR()
- SWITCH()

Text Functions

- CONCATENATE()
- UPPER()
- LEFT()

Date Functions

- YEAR()
- MONTH()
- EOMONTH()

Time Intelligence Functions

- TOTALYTD()
- SAMEPERIODLASTYEAR()
- DATESINPERIOD()
- DATESBETWEEN()

Filter Context Functions

- CALCULATE()
- FILTER()
- ALL()

---

Tools & Technologies

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Data Modeling
- Matrix Visual

---

Key Learnings

- Advanced DAX Calculations
- Data Modeling and Relationships
- Time Intelligence Analysis
- Filter Context Management
- KPI Development
- Matrix-Based Reporting

---

Project Outcome

Successfully developed a Power BI analytical model using advanced DAX calculations, calculated columns, measures, time intelligence functions, and matrix-based reporting to generate actionable business insights from sales and returns data.
