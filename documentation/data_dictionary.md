# Data Dictionary

Dataset: BMW Global Sales 2018–2025  
Source: Kaggle  
Rows: 3,000+  
Cleaned using: Microsoft Excel  

| Column | Type | Description |
|--------|------|-------------|
| Year | Integer | Sales year (2018–2025) |
| Month | Integer | Month number (1–12) |
| Region | Text | Sales region — Europe, China, USA, RestOfWorld |
| Model | Text | BMW model — 3 Series, 5 Series, X3, X5, X7, i4, iX, MINI |
| Units_Sold | Integer | Number of vehicles sold in that row |
| Avg_Price_EUR | Decimal | Average selling price in Euros |
| Revenue_EUR | Decimal | Calculated: Units_Sold × Avg_Price_EUR |
| BEV_Share | Percentage | Share of sales that are battery electric vehicles |
| Premium_Share | Percentage | Share of sales in the premium segment |
| GDP_Growth | Decimal | Regional GDP growth rate for that year |
| Fuel_Price_Index | Decimal | Fuel price index — base value 1.00 in 2018 |

## Data Cleaning Steps Performed
1. Removed duplicate rows
2. Formatted all date and number columns
3. Verified Revenue_EUR = Units_Sold × Avg_Price_EUR for every row
4. Converted BEV_Share and Premium_Share to percentage format
5. Checked for missing values — none found
6. Standardised Region and Model text values for consistency