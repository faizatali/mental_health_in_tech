# Exploring Mental Health in the Tech Industry

An interactive dashboard (Dash + Plotly) for exploring the **OSMI Mental Health in Tech Survey (2014)**. Filter respondents by **Country**, **Gender**, **Age (18–72)**, and **Work mode** (Remote/In-person) to instantly update KPIs and plots. The app uses the IBM/Carbon color palette and a clean, responsive layout with Dash Bootstrap Components.

---

## ✨ Features

- **Filters**: Country · Gender · Age (18–72) · Work mode (Remote / In-person / All)  
- **KPIs**:  
  - Respondents (after filters)  
  - Treatment rate (% answering “Yes”)  
  - *(Optional extras you can enable: Benefits coverage, Work interference (Sometimes+Often), Perceived consequences (Yes))*  
- **Charts (stacked within each company-size bin; bars sum to 100%)**  
  1) Treatment — *Yes / No*  
  2) Perceived mental-health consequence — *Yes / Maybe / No*  
  3) Benefits — *Yes / No / Don’t know*  
  4) Work interference — *Never / Rarely / Sometimes / Often*  
- **Design**: IBM/Carbon color palette; responsive layout with Dash Bootstrap Components  
- **Interactivity**: Hover for exact counts/percents; click legend items to isolate or mute categories

---

## 📊 Data

This app explores the **OSMI Mental Health in Tech Survey (2014)**, an open dataset of ~1,200 tech workers. The survey (by **Open Sourcing Mental Health, OSMI**) covers mental-health history, employer policies/benefits, perceived consequences, and workplace culture.

- Research page: https://osmhhelp.org/research.html  
- Place the cleaned CSV as `cleaned_data.csv` in the project root.

> **Note**: Missing values are excluded from charts for clarity. Company-size order used:  
> *1–5, 6–25, 26–100, 100–500, 500–1000, More than 1000*.

---

## 🧰 Tech Stack

- Python · Dash · Plotly Express · Dash Bootstrap Components  
- Pandas · NumPy

---

## 🚀 Getting Started

### 1) Setup environment (optional but recommended)
```bash
python -m venv .venv
# macOS/Linux
source .venv/bin/activate
# Windows
# .venv\Scripts\activate
