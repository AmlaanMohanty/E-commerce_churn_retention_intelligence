E-COMMERCE CHURN AND RETENTION ANALYTICS
========================================

Operational snapshot: 2011-09-01
Customer-score grain: one row per customer
Primary campaign grain: one row per selected customer

Recommended Power BI starting tables:
- 01_executive_kpis.csv
- 03_customer_risk_scores.csv
- 04_primary_campaign_targets.csv
- 05_risk_tier_summary.csv
- 06_retention_strategy_summary.csv
- 08_budget_scenarios.csv

Important interpretation notes:
- The churn model predicts 90-day purchase inactivity.
- Revenue at risk is probability-weighted exposure, not guaranteed lost revenue.
- Preserved revenue, net benefit and ROI depend on planning assumptions.
- actual_churn is a historical evaluation field and is not available in live deployment.
- Real retention uplift should be measured through a controlled campaign experiment.