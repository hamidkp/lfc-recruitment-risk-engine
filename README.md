# ⚽ Premier League Recruitment & Injury-Risk Engine (Liverpool FC Case Study)

An end-to-end Machine Learning scouting pipeline designed to evaluate player availability, physical durability, and transfer injury risk using historical Premier League records and real-time live API data.

## 📌 Project Overview
- **Core Objective:** Identify high-durability, low-risk transfer targets while filtering out injury-prone or overworked profiles.
- **Scouting Caliber Focus:** High-value budget gems under £6.0m across external Premier League squads.
- **Model Architecture:** Balanced RandomForestClassifier optimized to handle class imbalance in athletic availability.
- **Validation Metrics:** ROC-AUC: 0.805 | High-Absence Recall: 0.97

## ⚙️ Pipeline Highlights
- Direct integration with Premier League official Fantasy API (`bootstrap-static`).
- Dynamic separation between medical absence and tactical rotation using BPS and Threat indicators.
- Automated scouting filters isolating durable targets under £6.0m.

## 🚀 Installation & Usage
```bash
git clone [https://github.com/YOUR_USERNAME/lfc-recruitment-risk-engine.git](https://github.com/YOUR_USERNAME/lfc-recruitment-risk-engine.git)
cd lfc-recruitment-risk-engine
pip install -r requirements.txt
