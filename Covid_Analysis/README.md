# COVID-19 Global — Excel Analysis

## Security
- Formulas and data cells are locked
- Workbook structure protected
- File intended for read-only portfolio viewing

---

## Project Overview
This project presents a **COVID-19 Global Dashboard** developed using **Microsoft Excel** to analyze country-wise pandemic data from 2020–2021. The analysis focuses on infection spread, recovery trends, and mortality risk across regions, simulating the role of a **Junior Data Analyst** supporting a public health agency.

---

## Objectives
- Analyze global COVID-19 data using Excel
- Calculate key pandemic indicators
- Categorize countries based on risk levels
- Apply conditional formatting for visual insights
- Create charts to communicate trends effectively
- Provide data-driven insights for policy support

---

## Dataset Description
The dataset includes the following columns:
- Country  
- Confirmed Cases  
- Deaths  
- Recovered  
- Active Cases  
- Population  
- Continent  
- Date of First Case  

---

## Key Metrics & Calculations
The following metrics were calculated using Excel formulas:

- **Death Rate (%)** = Deaths / Confirmed Cases  
- **Recovery Rate (%)** = Recovered / Confirmed Cases  
- **Infection Rate (%)** = Confirmed Cases / Population  

### Risk Classification (IF / IFS)
- **High Risk** → Death Rate > 5%  
- **Moderate Risk** → Death Rate between 2%–5%  
- **Low Risk** → Death Rate < 2%

---

## Conditional Formatting
- High-risk countries highlighted in **red**
- **3-color scale** applied to Recovery Rate
- **Data bars** used for Infection Rate
- **Icon sets** (up / sideways / down arrows) to represent risk levels

---

## Visualizations
- **Column Chart**: Confirmed vs Recovered cases
- **Pie Chart**: Continent-wise case distribution
- **Combo Chart**:
  - Columns → Confirmed Cases
  - Line → Death Rate (%)

All charts are organized into separate worksheets for clarity.

---

## Lookup Functions
- **VLOOKUP** used to retrieve population details
- **HLOOKUP** used to identify continent information

---

## Insights & Analysis
The project answers key analytical questions such as:
- Which continents had higher recovery rates?
- Which countries fall into the high-risk category?
- How population size relates to confirmed cases
- Which countries handled the pandemic most efficiently
- Which visualizations best communicated critical insights

Insights are documented in the **Brainstorming Reflection** sheet.

---

## Tools Used
- Microsoft Excel  
  - IF / IFS Functions  
  - VLOOKUP & HLOOKUP  
  - Conditional Formatting  
  - Charts & Dashboards  
