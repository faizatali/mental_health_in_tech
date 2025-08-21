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

- **Filters**: country (dropdown menu), gender (radio buttons), age (slider ranging from 18 to 72), work mode (radio buttons)
- **KPIs**:  
  - Respondents - total number of respondents (after filters are applied)
  - Treatment - percentage of respondents who are receiving or have received mental health treatment
- **Charts**: stacked within each company-size bin; bars sum to 100%
  - Mental Health Benefits by Company Size
    - Question: Does your employer provide mental health benefits?
    - Categories: yes, no, don't know
  - Treatment by Company Size
    - Question: Have you recieved treatment for a mental health condition?
    - Categories: yes, no
  - Work Interference by Company Size
    - Question: If you have a mental health condition, do you feel that it interferes with your work?
    - Categories: never, rarely, sometimes, often, not applicable 
  - Perceived Mental Health Consequence by Company Size
    - Question: Do you think that discussing a mental health issue with your employer would have negative consequences?
    - Categories: yes, maybe, no, 
- **Design**: IBM/Carbon color palette; responsive layout with Dash Bootstrap Components  
- **Interactivity**: Hover for exact counts/percents; click legend items to isolate or mute categories

## Tech Stack

- Python, Dash, Plotly Express, Dash Bootstrap Components  

