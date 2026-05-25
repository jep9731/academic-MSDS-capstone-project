# 🎓 Healthcare Predictive Analytics — MSDS Capstone

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Program](https://img.shields.io/badge/Program-MSDS-blue)
![Section](https://img.shields.io/badge/Section-55-orange)
![Dashboard](https://img.shields.io/badge/Dashboard-Power%20BI-yellow)

> **Master of Science in Data Science — Northwestern University**
>
> A comprehensive healthcare analytics capstone project focused on predictive modeling, patient risk classification, hospital billing analysis, and interactive Power BI dashboard development.

---

# 📌 Project Overview

This repository contains the final deliverables for our MSDS Capstone project, developed as part of the Northwestern University Master of Science in Data Science program.

The project combines healthcare analytics, machine learning, financial analysis, and business intelligence to analyze hospital patient data and generate actionable operational insights.

The solution integrates:

- Predictive analytics for hospital billing estimation
- Patient risk classification modeling
- Exploratory healthcare data analysis
- Financial and operational reporting
- Interactive Power BI dashboards
- Automated dashboard-ready export pipelines

---

# 🏥 Business Problem

Healthcare organizations face increasing pressure to:

- Reduce operational costs
- Improve patient outcomes
- Identify high-risk patient populations
- Optimize hospital resource allocation
- Better understand healthcare billing drivers

This project addresses these challenges by analyzing patient admission, medical condition, demographic, and billing data to generate predictive and operational insights.

## Strategic Objectives

- Predict hospital billing amounts
- Classify patients into risk categories
- Analyze billing trends across medical conditions
- Understand operational drivers of hospital costs
- Deliver executive-ready dashboards for decision-making

---

# 🤖 Analytics & Modeling Objectives

The capstone contains two primary analytics initiatives:

## 1. Predict Hospital Billing Amount

Machine learning models are used to estimate patient billing amounts based on:

- Admission type
- Medical condition
- Length of stay
- Demographics
- Insurance provider
- Medication and test results

## 2. Patient Risk Classification

Classification models identify high-risk patient groups using engineered healthcare features and operational indicators.

Risk classification supports:

- Early intervention planning
- Resource prioritization
- Operational forecasting
- Cost management

---

# 📊 Power BI Dashboard

The project includes a multi-page Power BI dashboard built using exported datasets generated directly from the notebook pipeline.

## Dashboard Features

### Executive KPI Overview

Key metrics include:

| KPI | Value |
|---|---|
| Average Billing | ~$26K |
| Median Billing | ~$26K |
| Total Patients | ~55K |
| Average Length of Stay | 15.5 Days |
| High Risk Rate | 49.2% |
| High Risk Count | ~27K |

---

## Billing Analytics

Visualizations include:

- Average billing by medical condition
- Billing distribution analysis
- Billing comparison by admission type
- Length of stay vs. billing relationships
- Billing heatmaps by condition and admission type

### Key Findings

- Obesity and diabetes patients had the highest average billing amounts
- Emergency admissions consistently produced higher operational risk
- Billing increases correlated with longer patient stays

---

## Risk Classification Analytics

Dashboard pages analyze:

- Risk distribution across age groups
- High-risk patient counts
- Billing premium for high-risk populations
- Average stay duration by risk level
- Risk score comparison by admission type

### Key Findings

- High-risk patients incurred approximately **$3K higher billing costs**
- High-risk patients averaged significantly longer hospital stays
- Emergency admissions produced the highest average risk scores
- Older age groups showed elevated operational risk patterns

---

# 📓 Notebook Workflow

The primary notebook powering the project is:

```text
Capstone_Final.ipynb
```

The notebook contains:

1. Dependency installation
2. Configuration setup
3. Data loading and preprocessing
4. Exploratory Data Analysis (EDA)
5. Financial analysis
6. Billing amount prediction
7. Patient risk classification
8. Power BI export generation
9. Dashboard embedding support

---

# 🧪 Data Science Workflow

## 1. Data Acquisition

The dataset is downloaded and loaded using KaggleHub.

## 2. Data Cleaning & Engineering

Feature engineering includes:

- Length of stay calculations
- Date transformations
- Categorical encoding
- Risk score generation
- Operational feature creation

## 3. Exploratory Data Analysis

EDA identifies:

- Billing trends
- Admission behavior
- Patient demographics
- Medical condition distributions
- Operational patterns

## 4. Machine Learning Modeling

The project develops:

- Regression models for billing prediction
- Classification models for patient risk

Technologies include:

- Scikit-learn
- XGBoost
- Pandas
- NumPy

## 5. Dashboard Export Pipeline

Processed datasets are exported to CSV for direct Power BI integration.

Example export workflow:

```python
billing_export.to_csv("processed/billing_metrics.csv", index=False)
risk_export.to_csv("processed/risk_metrics.csv", index=False)
patient_export.to_csv("processed/patient_data.csv", index=False)
```

---

# 🗂️ Repository Structure

```text
📦 healthcare-capstone/
├── 📁 data/
│   ├── raw/                          # Original healthcare datasets
│   └── processed/                    # Dashboard-ready exports
│
├── 📁 notebooks/
│   └── Capstone_Final.ipynb          # Main capstone notebook
│
├── 📁 dashboards/
│   ├── healthcare_dashboard.pbix     # Power BI dashboard
│   └── healthcare_dashboard.pdf      # PDF of dashboard
│
├── 📁 reports/
│   ├── executive_summary.pdf
|   ├── final_report.pdf
│   └── final_presentation.pdf
│
├── requirements.txt
└── README.md
```

---

# 🛠️ Technology Stack

| Category | Tools |
|---|---|
| **Programming Languages** | Python, SQL |
| **Data Processing** | Pandas, NumPy |
| **Machine Learning** | Scikit-learn, XGBoost |
| **Visualization** | Power BI, Plotly, Matplotlib, Seaborn |
| **Notebook Environment** | Jupyter Notebook, Google Colab |
| **Data Source Management** | KaggleHub |
| **Version Control** | Git, GitHub |

---

# ⚙️ Getting Started

## Prerequisites

- Python 3.9+
- Jupyter Notebook or Google Colab
- Power BI Desktop
- Conda or virtualenv

---

# 🔧 Installation

```bash
# Clone repository
git clone https://github.com/your-org/healthcare-capstone.git

cd healthcare-capstone

# Create environment
conda env create -f environment.yml

# Activate environment
conda activate capstone

# Or install manually
pip install -r requirements.txt
```

---

# ▶️ Running the Project

## Launch the Notebook

```bash
jupyter notebook notebooks/Capstone_Final.ipynb
```

## Execute the Pipeline

Run notebook cells sequentially to:

- Load healthcare data
- Train models
- Generate KPIs
- Export Power BI datasets

## Open the Dashboard

```text
dashboards/healthcare_dashboard.pbix
```

Open the `.pbix` file using Power BI Desktop.

---

# 📈 Key Results

| Result | Outcome |
|---|---|
| High Risk Patient Rate | 49.2% |
| Average Billing | ~$26K |
| Billing Premium for High Risk Patients | ~$3K |
| Average Length of Stay | 15.5 Days |
| Total Patients Analyzed | ~55K |

Additional insights:

- Emergency admissions generated the highest operational risk scores
- Longer hospital stays strongly correlated with increased billing amounts
- Medical condition categories showed measurable cost variability
- High-risk patients required greater healthcare resource utilization

---

# 📄 Deliverables

- [x] Exploratory Data Analysis
- [x] Financial Analytics
- [x] Billing Prediction Models
- [x] Patient Risk Classification Models
- [x] Power BI Dashboard
- [x] Dashboard Export Pipeline
- [x] Final Presentation
- [x] Executive Reporting Visualizations

---

# 👥 Team Members

| Name | Role |
|---|---|
| `Joshua Pasaye` | Patient Risk Model Development / Dashboard Development |
| `Liam Reardon` | Data Analyst / Mobile App Development |
| `Ryan Hong` | Financial Analyst / Project Manager |
| `James Kwok` | Cost Optimization Model Development / Chatbot Integretation |
| `Eric Mallmann` | Chatbot Integration / Dashboard Development
| `Wildcats Analytics Partners` | MSDS Capstone Team |

---

# 🙏 Acknowledgments

We would like to thank the Northwestern University MSDS faculty, instructors, mentors, and peers who supported this capstone project.

Special thanks to the healthcare analytics and machine learning coursework that contributed to the successful implementation of this project.

---

# 📬 Contact

For questions or collaboration opportunities:

| Team Member | Email |
|---|---|
| `Joshua Pasaye` | `joshuapasaye2027@u.northwestern.edu` |
| `Liam Reardon` | `liamreardon2026@u.northwestern.edu` |
| `James Kwok` | `kameskwok2027@u.northwestern.edu` |
| `Ryan Hong` | `ryanhong2026@u.northwestern.edu` |
| `Eric Mallmann` | `ericmallmann2024@u.northwestern.edu` |

---

# 🚀 Future Enhancements

Potential future improvements include:

- Real-time healthcare dashboard integration
- Cloud deployment architecture
- Automated ETL scheduling
- Advanced predictive forecasting
- Deep learning risk classification
- HIPAA-compliant deployment pipelines
- Real-time hospital monitoring systems

---

*This project was completed in partial fulfillment of the requirements for the Master of Science in Data Science program at Northwestern University.*


