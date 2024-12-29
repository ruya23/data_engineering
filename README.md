# ISTA 322 FINAL PROJECT README

## Project Title
**Understanding the Effectiveness of Vaccinations and Booster Shots Against COVID-19 in the Year 2021**

---

## Student Information
- **Name:** Sarayu Gadi  
- **Class:** ISTA 322 (Fall 2024)  
- **Year:** Sophomore  
- **Institution:** University of Arizona  

---

## Project Overview

### Objective  
The primary goal of this project is to build a comprehensive data engineering pipeline that processes real-world data about COVID-19 cases and vaccinations. This pipeline transforms raw data into a structured format within a SQL database, enabling analysis to understand the effectiveness of vaccinations and booster shots in reducing severe COVID-19 outcomes during 2021.

### Purpose  
By analyzing census data and COVID-19 statistics, this project aims to uncover the impact of vaccination efforts on different populations. The results are intended to reveal patterns and trends that can support public health decision-making and enhance understanding of vaccine effectiveness.

### Usage  
This project focuses on the critical task of evaluating how vaccinations have influenced COVID-19 outcomes, such as reducing severe illness and fatalities. By leveraging a combination of COVID-19 case data, vaccination records, and demographic information, the analysis seeks to provide evidence-based insights into the vaccines' role in mitigating the pandemic's impact.

---

## Process Overview

1. **Extract**  
   Data is sourced from public health databases, government reports, and other reliable platforms that track COVID-19 cases, vaccination rates, and demographic details.

2. **Transform**  
   - The raw data is cleaned to handle errors like missing values and inconsistent formats.  
   - Standardization ensures uniformity across all datasets.  
   - New variables, such as weekly death percentages and vaccination coverage rates, are computed to enable deeper analysis.

3. **Load**  
   - The cleaned and standardized data is imported into a SQL database.  
   - Tables are created to store COVID-19 cases, deaths, vaccination records, and demographic details.  
   - SQL queries are employed to perform detailed analyses and identify meaningful trends.

---

## Analysis Goals
- Calculate the weekly casualty percentage per country.  
- Assess the effectiveness of two vaccine doses in reducing COVID-19 fatalities.  
- Examine the impact of booster shots on mortality rates.  

---

## Insights
By integrating data engineering principles with statistical analysis, this project aims to demonstrate vaccination effectiveness and support ongoing efforts to mitigate the effects of the COVID-19 pandemic.
