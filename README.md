# Online Retail — Power BI Reporting (CEO/CMO Dashboards)

This repository contains a complete Power BI project for the classic **Online Retail** dataset with:
- Cleaned dataset
- Executive-ready visuals (4 pages)
- Dark gradient theme
- Reusable DAX measures
- Assembly checklist

## Repo Structure
```
.
├── data/
│   └── OnlineRetail_Cleaned.csv
├── powerbi/
│   ├── theme/
│   │   └── DarkGradientTheme_FIXED.json
│   └── dax/
│       └── DAX_Measures.txt
├── docs/
│   ├── Assembly_Checklist.md
│   └── screenshots/   # add your report screenshots here
├── .gitattributes     # uses LFS for PBIX/ZIP (optional)
├── .gitignore
├── LICENSE
└── README.md
```

## Pages
1. **Summary Dashboard** — KPIs + Year slicer
2. **Q1_RevenueTrend** — Line chart, Month vs Revenue (2011)
3. **Q3_TopCustomers** — Top 10 customers by Revenue
4. **Q4_GlobalDemand** — Filled Map by Quantity (exclude UK)

## Quickstart
1. Open **Power BI Desktop**
2. Import `data/OnlineRetail_Cleaned.csv`
3. Apply theme from `powerbi/theme/DarkGradientTheme_FIXED.json`
4. Add measures from `powerbi/dax/DAX_Measures.txt`
5. Build visuals per `docs/Assembly_Checklist.md`
6. Save as `OnlineRetail_Analysis.pbix`

## Git LFS (optional for large .pbix)
```bash
git lfs install
git lfs track "*.pbix" "*.zip"
git add .gitattributes
git commit -m "chore: track pbix with git-lfs"
```

## License
MIT
