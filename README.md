# QTM 302W EDA Project — Group 3  
### *Education in Context: Exploring Long-Term Trends in U.S. School Indicators*  

**Course:** ENGRD/QTM 302W — Technical Writing for Data Science  
**Date:** October 2025  

---

## Description  
This project uses the **World Bank’s Education Statistics** dataset to explore long-term trends and relationships among key indicators of the U.S. education system.  
Our goal is to understand how structural aspects of education — such as access, staffing, and outcomes — have evolved over time, and how changes in one variable may (or may not) predict changes in another.  

The dataset spans several decades and allows us to analyze how participation and resource allocation shift across **school levels** (primary, secondary, tertiary) and **years** (2005–2022).  
By combining exploratory data analysis and regression modeling, we assess the strength and direction of relationships among variables that represent student participation and institutional investment.

---

## Analytical Focus  

We selected three major indicator categories representing different dimensions of the education system:

### 1. Enrollment Rate vs Attendance Rate  
- Investigates whether higher enrollment corresponds with consistent attendance over time.  
- Includes pre- and post-filtering distribution checks, correlation analysis, and linear regressions by school type.  
- **Finding:** Despite high average rates, correlations are weak and statistically insignificant, suggesting that increased enrollment does not reliably predict attendance.  

### 2. Number of Teachers vs Teaching Staff Compensation  
- Explores whether compensation levels rise proportionally with staffing levels across school stages.  
- Includes time-series plots, central tendency measures, and discussion of funding patterns.  
- **Finding:** Teacher counts remain stable while compensation increases slightly, implying that funding shifts may not directly affect staffing levels.  

### 3. (Planned) Educational Attainment by Sex  
- Tracks differences in educational outcomes between male and female populations over time.  
- Extends the analysis to measure broader social progress and equity if data coverage allows.  

---

## Motivation  
When brainstorming datasets, we initially considered public health and climate data but chose **education** because it is something we all experience and can interpret meaningfully.  
Education is a universal and policy-relevant domain, and its trends often reflect larger social and economic forces.  

As students in an American university, we were especially drawn to exploring national-level data.  
U.S. education policy and access have changed dramatically in recent decades, making it an ideal context for studying how participation and resource allocation interact.  
This project also gave us a chance to reflect on our own experiences — *how much do individual outcomes depend on student effort versus institutional support?*  

---

## Methods  
Our exploratory data analysis (EDA) was conducted in **R** using the `tidyverse`, `plotly`, and `broom` libraries.  
Following best practices for reproducible research, our notebook includes:  
- Data cleaning and restructuring into tidy long-form tables  
- Visual exploration of **pre- and post-filter distributions**  
- Descriptive statistics (mean, median, variance, quartiles, IQR)  
- Correlation and regression modeling to test variable relationships  
- Interactive visualizations using `plotly` for longitudinal comparisons  

---

## Key Findings  
- **High enrollment does not guarantee consistent attendance.**  
  Regression models show weak and statistically insignificant relationships between the two.  
- **Attendance rates have gradually declined**, especially in elementary schools, likely reflecting disruptions such as COVID-19.  
- **Teacher compensation has risen slightly while staffing remained stable**, suggesting policy or funding changes independent of employment levels.  
- Overall, **education indicators remain high but weakly related**, revealing structural independence among access, participation, and resource metrics.  

---
