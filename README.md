# QTM 302W Research Project — Group 3  
### *Pandemic-Era Changes in US Education*  

**Course:** ENGRD/QTM 302W — Technical Writing for Data Science  
**Date:** December 2025  
**Authors:** Anushka Basu, Minjoo Kim, Danielle Klewans

---

## Description  
This project uses the **World Bank’s Education Statistics** dataset to explore the impact of COVID 19 on US public school and relationships among key indicators of the U.S. education system.  
Our goal is to understand to what extent did the COVID 19 pandemic significantly altered student attendance and enrollment rate in the United States.  

The dataset spans several decades and allows us to analyze how participation and resource allocation shift across **school levels** (primary, secondary, tertiary) and **years** (2005–2022).  
By combining exploratory data analysis and regression modeling, we assess how the two major categories of enrollment and attendance reflect different dimensions of the education system.

---

## Analytical Focus  

We selected two major indicator categories representing different dimensions of the education system:

### 1. Enrollment Rate
- Compare student enrollment rates across different levels of schooling and different years.
- **Finding:** Small but statistically significant increase in average attendance following the pandemic.  

### 2. Attendance Rate
- Compare student attendance rates across different levels of schooling and different years.
- **Finding:** Did not change by a tangible amount before and after pandemic.

---

## Motivation  
When brainstorming datasets, we initially considered public health and climate data but chose **education** because it is something we all experience and can interpret meaningfully.  
Education is a universal and policy-relevant domain, and its trends often reflect larger social and economic forces.  

As students in an American university, we were especially drawn to exploring national-level data.  
Education policy and access here have evolved significantly over time, and exploring long-term patterns in enrollment and attendance can show how nation-wide policy changes and major events shape these measures. This matters to us as students who moved through all three levels of schooling and saw hour own efforts, most notably in high school, would determine our outcomes later in life.

Attendance and enrollment jump out to us as variables of interest due to their potential interaction with one another. Because we experienced schooling during COVID, we examine whether national trends reflect similar shifts. We test whether similar shifts appear at the national level.

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
- **Enrollment vs. Attendance**  
  Attendance rates are typically lower than enrollment rates at all levels, though the gap varies by level and year.  
- **Attendance rates have gradually declined**, especially in elementary schools, likely reflecting disruptions such as COVID-19.  
- Overall, **education indicators remain high but weakly related**, revealing structural independence among access, participation, and resource metrics.  

---
