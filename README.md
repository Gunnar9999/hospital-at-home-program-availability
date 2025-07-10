# Hospital-at-Home (HaH) Program Availability Analysis

## Project Overview  
This project explores the availability of Hospital-at-Home (HaH) programs across U.S. counties using 2022 data from the Area Health Resource Files (AHRF). It investigates how factors such as insurance coverage, rural-urban status, population size, and age demographics relate to the presence of HaH programs. The project blends logistic regression, interactive dashboarding, and public health analytics to identify key access gaps and inform policy expansion.

## Research Questions  
- **Primary:** Does a county’s insurance coverage rate significantly influence the availability of a Hospital-at-Home program?
- **Secondary:** How do population size, ruralness, hospital resources, and senior demographics correlate with HaH access?

## Tools Used  
- **Power BI** – Data modeling, visualization, and KPI tracking  
- **Excel & Power Query** – Data cleaning, feature creation, and transformations  
- **JMP Pro** – Logistic regression analysis and model interpretation  

## Key Deliverables  
- Developed logistic regression models to quantify factors most predictive of HaH program presence  
- Built an interactive Power BI dashboard to visualize urban/rural disparities, program clustering, and hospital capacity  
- Identified insurance coverage and population size as strong predictors, with minimal regional influence  
- Produced a written analysis with policy-focused recommendations to improve rural and underserved county access

## Files  
- `HaH_Dashboard.pbix` – Interactive Power BI dashboard  
- `HaH Hospitals - ISM6404.xlsx` – Dataset of counties with active HaH programs 
- `Term Project Final version.docx` – Final project report including full methodology, visuals, and conclusions  
- `ahrf2022 - HaH Data.xlsx` – County-level source data from AHRF
- `HaH Data Processing Output (version 1).xlsb.xlsx` – Cleaned and merged dataset used in the dashboard

## Summary of Findings  
- HaH programs are most common in urban counties with higher insured populations and larger hospital capacity  
- **Insurance coverage** and **population size** were statistically significant drivers of program access  
- **Veteran population percentage** and **hospital beds per 1,000 residents** also contributed positively  
- **Senior population %** and **region** were not significant predictors  
- The biggest HaH accessibility gaps are in rural and low-population counties with lower coverage rates

## Future Work  
- Explore predictive modeling by rural-urban category (RUCC subgrouping)  
- Include additional variables such as provider counts, Medicare/Medicaid penetration, or quality ratings  
- Test interaction terms (e.g., insurance coverage × senior population) to improve explanatory power


