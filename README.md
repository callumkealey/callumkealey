# Callum Kealey

**Data analysis • SQL • Python • Tableau • Operational decision support**

This portfolio shows how I prepare and analyse data, validate findings, and translate them into business and operational recommendations. The three projects below were completed as part of the **LSE Data Analytics Career Accelerator**.

## Selected projects

### 1. [Predictive Customer Analytics](https://github.com/callumkealey/predictive-customer-analytics)
**Python & R | Customer behaviour, statistical modelling and segmentation**

- **Question:** Which factors explain loyalty-point accumulation, and how could customer behaviour inform loyalty and marketing decisions?
- **Evidence:** Python regression and decision-tree modelling, a 70:30 train/test split, tree pruning, and scaled k-means clustering with elbow and silhouette comparisons. The R script adds multiple regression, residual diagnostics and scenario predictions.
- **Finding:** Spending behaviour was the strongest driver of loyalty points; the analysis identified five customer groups. The R validation records approximately 84% of variation explained by the multiple regression model.

[Python notebook](https://github.com/callumkealey/predictive-customer-analytics/blob/main/customer_behaviour_analysis.ipynb) · [R validation](https://github.com/callumkealey/predictive-customer-analytics/blob/main/statistical_validation.R) · [Technical report & recommendations](https://github.com/callumkealey/predictive-customer-analytics/blob/main/technical_report.pdf)

### 2. [SQL & Tableau Market Analysis](https://github.com/callumkealey/sql-tableau-market-analysis)
**SQL, Tableau & Excel | Customer demographics, sales and advertising**

- **Question:** How do purchasing patterns and advertising engagement vary across customer groups and countries?
- **Evidence:** SQL joins on customer ID, spending aggregation with `SUM` and `GROUP BY`, a derived household field, and intermediate tables joining country-level spending with social-media engagement. The report documents Tableau dashboard design, demographic filters and accessibility choices.
- **Finding:** Product-spending proportions varied relatively little between countries; the project identifies the need for time-series advertising and more detailed product data before drawing stronger conclusions.

[SQL script](https://github.com/callumkealey/sql-tableau-market-analysis/blob/main/market_analysis.sql) · [Report, dashboard design & visualisations](https://github.com/callumkealey/sql-tableau-market-analysis/blob/main/market_analysis_report.pdf)

### 3. [NHS Operational Capacity Analysis](https://github.com/callumkealey/nhs-operational-capacity-analysis)
**Python | Appointment demand, capacity and missed appointments**

- **Question:** How can appointment data support capacity planning and service improvement?
- **Evidence:** The project documents pandas date standardisation and monthly aggregation, data-quality checks, utilisation comparisons, and visual analysis of service settings, professional groups and attendance.
- **Recommendation:** Improved reminders, easier cancellations and alternative appointment modes were proposed to address missed appointments. Social-media data was treated as supplementary evidence because it was insufficiently NHS-specific.

[Python notebook & visualisations](https://github.com/callumkealey/nhs-operational-capacity-analysis/blob/main/nhs_operational_capacity_analysis.ipynb) · [Operational report & recommendations](https://github.com/callumkealey/nhs-operational-capacity-analysis/blob/main/nhs_operational_capacity_report.pdf)

## Where to find the technical evidence

| Skill | Evidence in this portfolio |
| --- | --- |
| SQL | Customer-ID joins, derived fields, grouped spending totals and intermediate tables in the market-analysis script |
| Python | Data preparation and exploratory analysis; regression, decision trees and clustering in the customer notebook; operational analysis in the NHS project |
| BI & visualisation | Tableau dashboard design documented in the market report; Python charts in the analytical projects |
| R & validation | Multiple regression, residual diagnostics and scenario predictions in the customer-validation script |
| Decision support | Findings, recommendations and limitations documented in all three project reports |

**Portfolio scope:** These are analytical case studies. Source datasets are not included in the repositories; the code and reports show the workflow and interpretation, but cannot be rerun from the repository files alone. The approximately 84% regression figure is explained variance, not a claim of 84% predictive accuracy or achieved business impact.

## Interests & contact

I’m interested in work where data, operations and strategy overlap, particularly service performance, operational improvement, transport and infrastructure.

[LinkedIn](https://www.linkedin.com/in/callum-kealey-25383024a/)
