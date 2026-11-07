# AdventureWorks: Financial Performance & Market Profitability Analysis (SQL)

## Project Overview
Acting as a Financial & Commercial Data Analyst for **AdventureWorks**, I explored, cleaned, and queried a 5-table relational database using **SQL** to evaluate revenue generation, cost structures, profit margins, and marketing Return on Investment (ROI) across global markets. The objective was to deliver a concise, data-driven executive summary to the Chief Financial Officer (CFO) to guide high-ROI marketing capital allocation.

## Database Architecture & Technical Execution
* **Relational Schema Exploration & Multi-Table Joins:** Mapped primary and foreign keys (`ClaveProducto`, `ClaveTerritorio`, `IDCampana`) to join five core enterprise tables (`ventas_2017`, `productos`, `productos_categorias`, `territorios`, and `campanas`) into a unified analytical view.
* **SQL Data Cleaning & Standardization:** Executed data wrangling directly in SQL, including handling `NULL` values (`COALESCE`), data type casting (`CAST`), and standardizing product and regional categories.
* **Financial & Marketing Investment Modeling:** Engineered calculated fields (`ingreso_total` = unit price × order quantity; `costo_total` = unit cost × order quantity) and integrated campaign investment expenditures (`campanas`) to compute **Gross Profit** (*Beneficio Bruto*), **Profit Margin** (*Margen*), and **Marketing ROI** across territories and product lines.
* **Data Quality Assurance (QA):** Performed reconciliation checks on financial totals, campaign costs, and margin boundaries to guarantee 100% reporting integrity.
* **Executive Communication (C→F→I Framework):** Synthesized query results and visualizations into a one-page executive brief structured under the **Context → Finding → Implication (C→F→I)** method to prioritize high-ROI regions and optimize underperforming campaigns.

## Tools & Technical Skills
* **SQL (Relational Databases):** Multi-Table `JOINs`, Relational Schema Mapping, Calculated Columns, Data Cleaning (`COALESCE`, `CAST`), Financial & Marketing ROI Modeling, Data QA Validation.
* **Business Intelligence:** Executive One-Pager Design, Data Visualization, C→F→I Strategic Storytelling.

## Project Files
* **Executive Summary Report (PDF):** `AdventureWorks_SQL_Executive_Summary.pdf` *(Click the file in the repository above to view the full one-page C→F→I report and visualizations directly in your browser)*

---
*Case study developed as part of the TripleTen Data Analytics Program.*
