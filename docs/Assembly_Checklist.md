# Assembly Checklist (Power BI)

## Pages
- Summary Dashboard (KPI cards + Year slicer)
- Q1_RevenueTrend (Monthly Revenue, 2011)
- Q3_TopCustomers (Top 10 by Revenue)
- Q4_GlobalDemand (Filled Map by Quantity, exclude UK)

## Steps
1. Import `data/OnlineRetail_Cleaned.csv`
2. Apply theme: `powerbi/theme/DarkGradientTheme_FIXED.json` (View → Themes → Browse)
3. Create measures from `powerbi/dax/DAX_Measures.txt`
4. Build visuals per spec above
5. Save as `OnlineRetail_Analysis.pbix`
