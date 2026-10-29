# Callum Kealey

**Data analytics · Python & SQL · Operational and investment decision support**

I work on practical analytical problems: preparing and validating data, building models, and turning results into decisions that can be explained and challenged. My portfolio combines three case studies from the **LSE Data Analytics Career Accelerator** with a newer, self-directed software project focused on asset investment planning.

**Areas of interest:** operational performance, infrastructure and investment planning, risk and assurance, and strategic reporting.

## Featured project

### [Asset Investment Planning Copilot](https://github.com/callumkealey/asset-investment-copilot)

**Python · pandas · SciPy/HiGHS · FastAPI · Streamlit · SQLite · OpenAI API · pytest**

An independent, reproducible prototype exploring how operational asset-condition data can change capital-investment decisions. It connects a simulated enterprise asset-management REST API to data validation, transparent project scoring, mixed-integer portfolio optimisation, an interactive what-if interface and an AI copilot that uses explicit tools and document retrieval.

- **Decision model:** 40 synthetic candidate projects, alternative strategic weightings, mandatory investments and capital-budget constraints.
- **Testable result:** Under a £250m budget, changing one asset's condition from 8 to 5 causes project **P033 to enter** the funded portfolio and **P022 to leave**. These are synthetic allocation decisions, not realised financial savings.
- **Engineering evidence:** 15 automated tests, a 15-scenario budget/condition sensitivity analysis, and GitHub Actions CI.

[Source and technical README](https://github.com/callumkealey/asset-investment-copilot) · [Sensitivity analysis](https://github.com/callumkealey/asset-investment-copilot/blob/main/docs/sensitivity_analysis.md) · [Automated tests](https://github.com/callumkealey/asset-investment-copilot/actions)

[![Asset-impact comparison in the Streamlit prototype](https://raw.githubusercontent.com/callumkealey/asset-investment-copilot/main/docs/Images/asset-impact.png)](https://github.com/callumkealey/asset-investment-copilot/blob/main/docs/Images/asset-impact.png)

*Streamlit screenshot showing a controlled, synthetic before-and-after funding comparison.*

## Analytics case studies

### [Predictive Customer Analytics](https://github.com/callumkealey/predictive-customer-analytics)
**Python & R · Predictive modelling · Customer segmentation**

Regression, pruned decision-tree modelling, scaled k-means clustering and review sentiment analysis to investigate loyalty behaviour. The accompanying R analysis adds regression diagnostics and scenario predictions; its multiple regression explains approximately **84% of observed loyalty-point variation**, not 84% predictive accuracy.

[Python notebook](https://github.com/callumkealey/predictive-customer-analytics/blob/main/customer_behaviour_analysis.ipynb) · [R validation](https://github.com/callumkealey/predictive-customer-analytics/blob/main/statistical_validation.R) · [Technical report](https://github.com/callumkealey/predictive-customer-analytics/blob/main/technical_report.pdf)

### [SQL & Tableau Market Analysis](https://github.com/callumkealey/sql-tableau-market-analysis)
**SQL · Tableau · Excel · Commercial analytics**

Customer and sales analysis using SQL joins, grouped aggregations, derived fields and intermediate tables. The accompanying report covers Tableau dashboard design, demographics, advertising engagement and the limits of cross-country comparisons.

[SQL script](https://github.com/callumkealey/sql-tableau-market-analysis/blob/main/market_analysis.sql) · [Dashboard design and report](https://github.com/callumkealey/sql-tableau-market-analysis/blob/main/market_analysis_report.pdf)

### [NHS Operational Capacity Analysis](https://github.com/callumkealey/nhs-operational-capacity-analysis)
**Python · pandas · Operational analytics**

Analysis of appointment demand, utilisation and missed appointments, including data-quality checks, time-based aggregations and service comparisons. The report translates findings into potential service improvements while acknowledging the limits of supplementary social-media evidence.

[Python notebook](https://github.com/callumkealey/nhs-operational-capacity-analysis/blob/main/nhs_operational_capacity_analysis.ipynb) · [Operational report](https://github.com/callumkealey/nhs-operational-capacity-analysis/blob/main/nhs_operational_capacity_report.pdf)

## Technical evidence at a glance

| Area | Examples in this portfolio |
| --- | --- |
| **Python & analytical modelling** | pandas analysis; regression, decision trees and clustering; investment scenario scoring |
| **SQL** | Joins, aggregation, derived fields and intermediate tables in the market-analysis project |
| **Visualisation & reporting** | Tableau dashboard design, analytical reports, Python charts and Streamlit interfaces |
| **Integration & software engineering** | REST API, asset-ID reconciliation, SQLite, tool-calling agent, automated pytest checks and CI |
| **Decision support** | Capital-budget optimisation, sensitivity testing, operational recommendations and explicit model limitations |

**Scope:** The Copilot is a synthetic personal project, not a commercial deployment or a validated capital-planning model. The original datasets for the three LSE case studies are not included in their repositories; their notebooks, scripts and reports document the methods and findings.

## Connect

[LinkedIn](https://www.linkedin.com/in/callum-kealey-25383024a/)
