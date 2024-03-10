### Data Professional Survey Analysis Using PowerBI

### Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Insights](#insights)
- [Limitations](#limitations)
- [References](#references)

---

### Project Overview
---
This dataset is collected as part of the survey conducted online to check different aspects and trends of Data professionals.

Task- Use the data set provided for this project and analyze that to understand the data and terms and provide insights.

### Data Sources 

Data: The primary dataset used for this analysis is the "Data Professional Survey-Data.xlsx" file,
containing survey questions and information. This LinkedIn survey was conducted by Alex Freberg in 2022 and several data professionals' answers were collected to determine the happiness ratings of data professionals. 

### Tools 
Tools used for Data Cleaning, Data Analysis and Report generation :
- PowerBI

### Data Cleaning

In the initial data preparation phase, I performed the following tasks:
- Data loading and inspection,
- Changing data types, splitting columns like salary, industry and job title to get more standard details 
- Optimizing the dataset by removing unnecessary and duplicate columns,
- Standardizing abbreviations used in the dataset,
- Handling missing values,
- Data cleaning and formatting,
- Managing Relationships between different tables.

### Exploratory Data Analysis

EDA involved exploring the data to answer key questions, such as:

- What are the happiness ratings of data professionals in terms of salary and work-life balance?
- What are the salary and trends reported per gender and job title?
- What is the most used or preferred programming language used for analysis?
- Demography of surveyors

### Data Analysis
- Created calculated columns for a more standard format 
- Advanced visualization charts like Funnel, gauge meter, map charts etc.
- Customized dashboard.

  ![Data Professional Survey](https://github.com/SmitaPinjan/Data-Professional-Survey-Analysis-Using-PowerBI/assets/152721562/26bcacc0-bdc5-46a4-b637-67b5cd941f40)

### Insights

The Analysis results are summarized as follows:
- A total of 630 unique surveyors voted and answered different questions related to the data profession. The average age of the surveyors was 30 years and these professionals majority from the US, India, Canada and the UK.
- The preferred programming language used is Python followed by R and SQL.
- The Happiness rating for work-life balance recorded is 5.74 and for salary is 4.27 out of 0 to 10 rating score.

### Limitations

I have listed some of the limitations which may affect the outcomes in terms of salary. 
- In the original survey, the salary recorded was in the format of 0-40K, or 90k-150K, and with a different format. So, to standardize, I have split the column and created an average salary column using the minimum and maximum ranges of those columns. So, it is closer to outcomes but may have affected the ranges.
- Demography is also important as the majority of surveyors are from the US where the average salary is higher. However, the second most surveyors are from India where salary is less compared to the US and other Western countries. The minimum salary range is also different when comparing the market rates in respective countries and it may affect the salary outcomes.

### References

- Microsoft guide for Power BI

|Heading1|Heading2|
|--------|--------|
|Content |Content2|
|Data Analysis| PowerBI|


