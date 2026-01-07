# Customer Support Ticket Resolution Analysis

This project analyses customer support ticket data to identify which departments experience the greatest resolution delays and where process improvements may have the highest impact.

The analysis was conducted in Excel using simulated real-world data containing mixed date formats, missing values, and inconsistent department naming.

## What was done
- Cleaned and standardised date fields
- Derived ticket status (Open / Closed)
- Calculated resolution times and flagged invalid records
- Standardised department naming conventions
- Analysed department-level performance using averages and medians
- Documented data issues and analytical decisions
- Produced an executive summary with findings and recommendations

## Key insights
- Customer Support has the greatest operational impact from delays due to high ticket volume and outlier-driven resolution times.
- IT resolution times are consistent, indicating uniformly complex ticket handling.
- Billing resolves most tickets quickly, with delays concentrated in a small number of complex cases.
- Tickets with unknown department classification highlight data quality and routing issues.

## Recommendation
Targeted process improvements in Customer Support, particularly around prolonged or escalated cases, are likely to deliver the greatest reduction in overall resolution delays.

## Next steps
This analysis will be reproduced in R to demonstrate programmatic data cleaning and reproducibility.
