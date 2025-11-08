# TDI-ESG-Financial-Performance-Analysis
Excel Capstone Project analyzing the relationship between ESG metrics and financial performance for strategic investment insights.

## Table of Conetnts

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Data Analysis](#data-analysis)
- [Results](#results)


### Project Overview

This project analyzes how ESG (Environmental, Social, and Governance) performance relates to financial metrics like profit margin, revenue, and carbon emissions across industries from 2015 to 2025. It was done in Excel using pivot tables and dashboards to uncover trends and insights for sustainable business decisions.

<img width="1663" height="802" alt="ESG DASHBOARD" src="https://github.com/user-attachments/assets/cada2945-117c-4017-b503-1df008e41340" />


### Data Sources

The dataset was provided by The Data Immersed (TDI) Community for the Excel Capstone Project. It includes ESG and financial performance data for 1,000 companies across multiple industries, covering the period from 2015 to 2025.

ESG & Financial Performance Data:

### Tools

- Excel - Data Cleaning, Data Analysis & Data Visualization

### Data Cleaning

1. Checked for and confirmed no duplicate records in the dataset.
2. Filtered each column to identify missing values.
3. Only the Growth Rate column had missing values — 1,000 rows from 2015, the base year.
4. Replaced missing growth rates with 0, assuming no prior data meant no growth.
5. Created two new columns:
    - ESG Category – classified ESG scores as Low, Moderate, or High.
    - Growth Rate Category – grouped growth rates into Negative, Neutral, or Positive.

### Exploratory Data Analysis (EDA)

1. Which industries demonstrate the highest and lowest average ESG scores?
2. Is there a correlation between ESG scores and profit margins?
3. Which industries generate the highest average revenue annually?
4. How have ESG scores changed over time?
5. Which companies are carbon emission outliers within their industries?

### Data Analysis

- Created pivot tables to break down ESG performance, profit margins, revenue, and carbon emissions by industry.
- Categorized ESG scores and revenue growth rates into defined performance groups.
- Used slicers (Year, Region, Growth Rate Category) for interactive filtering.
- Developed visual KPIs to track ESG Score, Revenue, and Profit across selected segments.
- Built a dashboard in Excel to summarize and visualize key insights.

### Results

- Finance and Technology industries recorded the highest average ESG scores, indicating stronger sustainability performance.
- The transportation and Energy sectors had the lowest average ESG scores, reflecting weaker ESG practices.
- Companies with high ESG scores achieved an average profit margin of 12.7%, compared to 10.6% for others.
- ESG scores increased consistently from 62 in 2015 to 74 in 2025, showing industry-wide improvement in sustainability efforts.
- Top 5 industries by average revenue included Technology, Finance, and Consumer Goods, contributing significantly to overall revenue performance.
- Outlier analysis on carbon emissions revealed that some companies within high-emitting industries greatly exceed their peers, especially in the Energy and Transportation sectors.

### Recommendations

- Investors should consider ESG performance as part of their evaluation framework, especially in high-performing sectors.
- Industries with lower ESG scores (e.g., Energy, Transportation) should review their sustainability policies and practices.
- Companies with low profit margins and low ESG scores may benefit from reassessing governance and operational efficiencies.
- Continued monitoring of ESG trends is crucial for forecasting long-term financial health and social impact.

### Limitations

- **Anonymous Company Identifiers**: The dataset used coded company names, which limited the ability to perform real-world, company-specific analysis or draw recognizable insights.
- **Missing Growth Rate Data (2015)**: Growth rate values for the base year (2015) were entirely missing. These were assumed to be zero to maintain analysis consistency, which may slightly affect the interpretation of early-year trends.
