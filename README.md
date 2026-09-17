# Canada-Anti-Fraud-Centre-National-Fraud-Trend-Analysis
This project analyzes Canadian Anti-Fraud Centre (CAFC) fraud reporting data to identify national patterns in reported fraud, financial losses, fraud categories, solicitation channels, geographic distribution, and victim age groups.  The objective is to transform reported fraud data into clear insights that can support fraud-prevention strategy.


Business Problem


Fraud affects Canadians differently across fraud categories, communication channels, provinces, and age groups. However, looking only at the number of reports does not provide a complete picture of the problem.

A fraud category may generate a large number of reports while producing relatively small individual losses, while another category may involve fewer reports but result in substantially higher financial losses.

This project therefore examines fraud from multiple perspectives to identify where reported losses are concentrated and which patterns may require greater attention.




Project Objectives



The study pursued these objectives:

- Clean and standardize CAFC reporting data to create an analysis-ready dataset.
- Analyse and identify national fraud patterns across categories, provinces, demographics, age groups, gender, and solicitation channels.
- Compare fraud categories using both report/victim volume and reported financial losses.
- Use Machine Learning to make predictions for the upcoming fraud categories identified.
- Develop data-supported recommendations for fraud-prevention strategy.


Data & Scope

- Source: Canadian Anti-Fraud Centre Fraud Reporting System data, accessed through open data portal
- Geographic scope: Canada
- Period analyzed: 2021–2024

The analysis uses reported fraud information and therefore reflects reported activity rather than the complete number of fraud incidents occurring in Canada




Data Preparation

The raw reporting data was prepared for analysis through data cleaning and standardization.

Key preparation activities included:

- Handling missing values consistently
 Standardizing relevant fields
- Removing duplicate records
- Preparing fraud categories and reporting attributes for analysis
- Creating age-group classifications
- Restricting the analysis to Canadian records
- Preparing variables required for descriptive and predictive analysis

The goal was to create a consistent dataset that could support reproducible analysis and visualization.



Analytical Approach



The analysis examined fraud from several perspectives:

1. National Trends

Examined changes in reported fraud losses and report volumes between 2021 and 2024.

2. Fraud Category

Compared categories based on reported financial losses, report volume, victimization rate, and average loss per case.

3. Solicitation Channel

Compared contact methods based on report volume, financial loss rate, and average loss per report.

4. Geographic Analysis

Compared reported losses across provinces and territories using both total losses and loss per resident.

5. Demographic Analysis

Examined reported losses across victim age groups and analyzed fraud types by age group.

6. Predictive Analysis

Used reporting attributes to examine whether characteristics such as fraud category, solicitation channel, province, and age group could help predict online fraud or high-loss outcomes.


