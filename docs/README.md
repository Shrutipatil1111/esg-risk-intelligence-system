# 🌍 ESG Risk Intelligence Platform  
**Version 1.0 – 2025**  
*Built with Python (Jupyter Notebook) & Power BI*  

---


## 🧭 Executive Summary

The ESG Risk Intelligence Platform enables assessment of environmental, social, governance, financial, and reputational risks across a portfolio of companies.

- ✅ Built with Python (Jupyter Notebook) for data simulation, scoring, and explainability  
- 📊 Visualized in Power BI for CXO-ready insights  
- 📋 Aligned with SEBI BRSR and TCFD disclosure frameworks  

---


## 🧱 Solution Architecture

| Layer           | Technology         | Description                                                             |
|-----------------|--------------------|-------------------------------------------------------------------------|
| Data Simulation | Jupyter Notebook   | Synthetic ESG, financial, and sentiment data (Faker, NumPy)             |
| Enrichment      | Jupyter Notebook   | Adds climate risk, controversy flags, sentiment scores                  |
| Scoring Engine  | Jupyter Notebook   | Normalization, weighting, CRI computation                               |
| Explainability  | Jupyter Notebook   | Generates natural language narratives per company                       |
| Diagnostics     | Jupyter Notebook   | Validates scoring logic and CRI distribution                            |
| Dashboard       | Power BI Desktop   | Interactive summary, drilldowns, benchmarking                           |

---


## 📁 Repository Structure
```text
ESG_Risk_Intelligence/
├── notebooks/
│   └── ESG_Risk_Intelligence_System.ipynb 
├── data/
│   └── ESG_Enhanced_Raw_Data.csv
├── output/
│   └── ESG_Risk_Scored_Output.csv
├── dashboard/
│   └── ESG_Risk_Intelligence.pbix
├── docs/
│   ├── README.md
│   ├── executive_briefing.pdf
│   └── screenshots/
│       ├── executive_summary.png
│       ├── company_deep_dive.png
│       ├── industry_comparison.png
│       └── geographical_analysis.png
```
---


## ⚙️ Setup Instructions

```bash
# Clone the repo
git clone https://github.com/yourusername/esg-risk-intelligence-platform.git
```

## Install requirements
``` bash
pip install pandas numpy scikit-learn faker
```
- Open ESG_Risk_Intelligence_System.ipynb in Jupyter Notebook

- Open ESG_Risk_Intelligence.pbix in Power BI Desktop

## ▶️ Run Instructions
- **Generate Data** – Run the notebook to create synthetic ESG data

- **Score Companies** – Compute pillar scores, CRI, and risk levels

- **Diagnostics** – Validate scoring logic and explore company-level insights

- **Visualize** – Load ESG_Risk_Scored_Output.csv into Power BI

## 📥 Sample Data

### Input (ESG_Enhanced_Raw_Data.csv)

Company Name

Industry

Scope 1/2 Emissions

Water Intensity

Financial Ratios

Sentiment Score

Disclosure Flags

### Output (ESG_Risk_Scored_Output.csv)

Composite Risk Index (CRI)

Risk Level (🔴 High / 🟡 Medium / 🟢 Low)

ESG Pillar Scores

Narrative Risk Explanation



## 🧪 Methodology
- **Normalization** – MinMaxScaler applied to all metrics

- **Materiality Weighting** – Industry-specific ESG pillar weights

- **Scoring** – Weighted aggregation into CRI (0–100 scale)

- **Classification** – Risk levels based on CRI thresholds

- **Explainability** – Rule-based narrative generation per company



## 💼 Business Impact
- 📈 Proactive portfolio monitoring for asset managers

- 📋 Regulatory readiness (SEBI BRSR, TCFD)

- 🚨 Early identification of high-risk companies

- 🤝 Stakeholder trust via explainable scoring

- 🌍 Climate overlays for geospatial risk insights



## 🔁 Versioning & Audit Trail
See docs/changelog.md for full update history.

Version	Date	Notes
1.0	Sept 2025	Initial release with scoring engine & dashboard


## 🧾 Executive Briefing
Delivered a full-stack ESG Risk Intelligence Platform using Jupyter Notebook and Power BI. Simulated and scored 30 companies across 10 industries. Enabled stakeholder-ready insights with explainable scoring, controversy tracking, and climate overlays. Designed for CXO decision-making, regulatory compliance, and portfolio risk mitigation.

📄 View the full briefing: docs/executive_briefing.pdf



## 👤 Ownership & Contact
Author: Shruti Patil Role: Solution Architect & Data Analyst – ESG Risk Intelligence

All modules are protected against unauthorized edits. Enhancement suggestions welcome via GitHub Issues or private message.
