DAX Depo – Advanced DAX Calculations in Power BI

Project Overview

DAX Depo is a Power BI project focused on building advanced analytical calculations using DAX (Data Analysis Expressions). The project demonstrates data modeling, calculated columns, measures, and business KPI creation using a Sales and Returns dataset.

---

Objective

The objective of this project is to create meaningful business insights using DAX functions and a well-structured data model without relying on multiple visualizations.

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

"Model View" (<img width="1920" height="1080" alt="modelview" src="https://github.com/user-attachments/assets/1a7ec58a-b4c2-4468-808d-c2794607e676" />)


---

Calculated Columns

The following calculated columns were created:

Sales_Fact

- Profit = SalesAmount - Cost
- ReturnFlag = Returned / Not Returned

Customer_Dim

- Customer Full Name

Calculated Columns Preview

"Calculated Columns" (<img width="1920" height="1080" alt="calculated columns" src="https://github.com/user-attachments/assets/14f7c145-f488-4689-8d8c-39123739396e" />)


---

Measures Created

The following DAX measures were implemented:

- Total Sales
- Total Cost
- Total Profit
- Return Rate
- Average Sale per Transaction
- Year-over-Year Sales Growth
- Previous Month Sales Difference

Measure Table

"Measure Table" (<img width="1920" height="1080" alt="measure_table" src="https://github.com/user-attachments/assets/7f0aa659-5ba1-48e9-850a-221b824687dd" />)


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

Tools Used

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Data Modeling

---

Key Learnings

- Data Modeling and Relationships
- Calculated Columns
- DAX Measures
- Time Intelligence
- Filter Context Analysis
- Business KPI Development

---

Project Outcome

Successfully developed a Power BI analytical model using advanced DAX calculations, calculated columns, and measures to generate business insights from sales and returns data.
