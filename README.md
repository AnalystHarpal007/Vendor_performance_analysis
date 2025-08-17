# Vendor_performance_analysis

vendor-performance-analytics/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── data/
│   ├── raw/
│   │   └── vendor_transactions_sample.csv        # put your raw file(s) here
│   ├── interim/
│   └── processed/
│
├── notebooks/
│   ├── 01_eda_vendor_performance.ipynb
│   ├── 02_profitability_modeling.ipynb
│   └── 03_inventory_turnover_analysis.ipynb
│
├── sql/
│   ├── create_tables.sql
│   ├── vendor_kpis.sql
│   ├── pricing_promotions_candidates.sql
│   └── slow_movers_inventory.sql
│
├── src/
│   ├── __init__.py
│   ├── utils.py
│   ├── preprocess.py
│   └── kpis.py
│
├── reports/
│   ├── figures/
│   └── Vendor_Performance_Report.pdf             # your PDF report (for reference)
│
