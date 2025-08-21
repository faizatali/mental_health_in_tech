# Exploring Mental Health in the Tech Industry

An interactive dashboard (Dash + Plotly) for exploring the **OSMI Mental Health in Tech Survey (2014)**. Filter respondents by **Country**, **Gender**, **Age (18–72)**, and **Work mode** (remote or in-person) to instantly update KPIs and plots. The app uses the IBM/Carbon color palette and a clean, responsive layout with Dash Bootstrap Components.

---

## Data

This app utilizes data collected by **OSMH (Open Source Mental Health)**, a non-profit organization dedicated 
to raising awareness and reducing stigma surrounding mental illness within the tech and developer community.

The OSMI Mental Health in Tech Survey is conducted annually and the data is made publicly available on the 
OSMH website. This specific dataset is from the 2014 study and contains over 1200 responses from individuals 
working in the tech industry. It includes questions regarding mental health history, employer support, perceived 
consequences, and workplace culture.

Dataset: https://osmhhelp.org/research.html

## Features

- **Filters**: Country · Gender · Age (18–72) · Work mode
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


## Tech Stack

- Python · Dash · Plotly Express · Dash Bootstrap Components  
- Pandas · NumPy
