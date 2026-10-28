# Advanced Excel Financial Modeling & Pivot Dashboard

## Project Overview
This workbook analyzes simulated sales data and presents revenue, cost, profit, margin, units sold, product performance, regional performance, and monthly trends.

## Workbook Sheets
- `Sales_Data` — source records and calculated financial columns.
- `Financial_Model` — KPI summary and basic validation checks.
- `Pivot_Dashboard` — executive-style dashboard with four KPI cards and three charts.
- `Region_Pivot`, `Product_Pivot`, `Monthly_Pivot` — formula-based summaries that feed the dashboard charts.
- `Native_Region_Pivot`, `Native_Product_Pivot`, `Native_Monthly_Pivot` — native PivotTables based on the source data.
- `Read_Me` — project guide and instructions.

## Tools
Microsoft Excel formulas, Excel Tables, PivotTables, charts, and financial calculations.

## Native PivotTables
Three native PivotTables are included:
- Regional performance: Region in Rows; Revenue, Profit and Units Sold in Values.
- Product performance: Product in Rows; Revenue, Profit and Units Sold in Values.
- Monthly performance: Order Date in Rows; Revenue and Profit in Values.

## Interactive Slicers — One Remaining Manual Step
Interactive Excel slicer objects could not be embedded automatically in this generated workbook. To add them in desktop Excel:
1. Open one of the `Native_*_Pivot` sheets and click inside its PivotTable.
2. Choose **PivotTable Analyze → Insert Slicer**.
3. Select `Region` or `Product`, then click **OK**.
4. To control multiple PivotTables, use **Slicer → Report Connections** and select compatible PivotTables.
5. Save the workbook and test the slicer before submission.

## Sample Financial Metrics
Based on the included 12 simulated orders:
- Total revenue: ₹439,000
- Total cost: ₹319,500
- Total profit: ₹119,500
- Overall profit margin: 27.22%
- Units sold: 102
- Orders: 12

## Data Source
Simulated practice data created for this project; it is not actual company data.

## Validation
The workbook includes revenue and profit checks. Verify calculations and test the native PivotTables in desktop Excel before submission.

## Key Findings
Laptop is the highest-revenue product in the sample. Compare region profit and monthly revenue in the dashboard. This small simulated dataset should not be treated as real business performance.

## Future Improvements
- Add and test interactive slicers.
- Expand to a larger dataset.
- Add budget-versus-actual analysis and forecasting.
