# Sales Data Analysis & Dashboard

An internship project where I analysed the Superstore sales dataset using **Excel**, **Python (Pandas)** and **Power BI** to find out what drives sales and profit, and where the business is losing money.

---

## What This Project Is About

Sales numbers alone don't tell you if a business is doing well. A product or state can sell a lot and still lose money. This project looks at the full picture: cleaning the data, calculating KPIs, exploring trends, and building an interactive dashboard, then turning the results into simple recommendations.

## Dataset

| Detail | Value |
| --- | --- |
| Dataset | Superstore Sales |
| Records | 9,994 |
| Columns | 21 |
| Date range | 03 Jan 2014 to 30 Dec 2017 |
| Orders | 5,009 |
| Customers | 793 |

Each row is one order line, with order, customer, location, product, and financial details (Sales, Quantity, Discount, Profit).

## Tools Used

- **Microsoft Excel**: data preparation, KPI calculations and detailed analysis
- **Python (Pandas, NumPy) on Google Colab**: repeating the analysis to double-check the Excel results
- **Power BI Desktop**: interactive dashboard
- **CSV**: cleaned dataset shared across all three tools

## How I Did It

1. **Understood the data**: went through every column and its meaning.
2. **Checked and cleaned**: no missing values or duplicate rows were found. I kept negative profits because they are real losses, not errors.
3. **Analysed in Excel**: separate sheets for KPIs, time, products, categories, regions and customers.
4. **Validated in Python**: reproduced the results and confirmed the totals match.
5. **Built the dashboard in Power BI**: four pages with Year, Region and Category filters.

## Key Results

| KPI | Value |
| --- | --- |
| Total Sales | $2,297,200.86 |
| Total Profit | $286,397.02 |
| Profit Margin | 12.47% |
| Average Order Value | $458.61 |
| Units Sold | 37,873 |

## Main Findings

- **Growth:** Sales dipped 2.83% in 2015, then grew 29.47% in 2016 and 20.36% in 2017.
- **Technology** earned the most profit ($145,454.95) with a 17.40% margin.
- **Furniture** had high sales ($741,999.80) but only a 2.49% margin.
- **Tables** lost money overall (-$17,725.48) despite $206,965.53 in sales.
- **West** was the best region with the highest sales and a 14.94% margin.
- **High sales don't mean high profit:** Texas lost $25,729.36 and Pennsylvania lost $15,559.96 despite large sales.

## Dashboard Pages

| Page | What it shows |
| --- | --- |
| Executive Dashboard | KPI cards, trends, top products and customers |
| Sales Analysis | Yearly trends, category and region comparisons |
| Product & Category | Best and worst products, sub-category profitability |
| Customer & Regional | Customer, segment, region and state performance |

## Recommendations

- Build on the strong Technology performance.
- Review Furniture pricing and discounts.
- Investigate Tables before selling more of them.
- Study what West does well and see if other regions can copy it.
- Track states and customers with high sales but low or negative profit.

## Repository Structure

> Placeholder names. Rename these to match your actual files.

```
├── data/
│   └── superstore_cleaned.csv
├── excel/
│   └── Superstore_Analysis.xlsx
├── python/
│   └── Superstore_Analysis.ipynb
├── powerbi/
│   └── Superstore_Dashboard.pbix
├── report/
│   └── Superstore_Sales_Analysis_Project_Report_Final.docx
└── README.md
```

## Limitations

This analysis is based on historical data. It shows what happened, not why. Any business decision based on it would need further investigation.

## Author

**Manu**, Internship Project
