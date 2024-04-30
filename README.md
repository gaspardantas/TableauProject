# Florida Housing Market Analysis

## Table of Contents
1. [Overview](#overview)
2. [Objectives](#objectives)
3. [Data Source](#data-source)
4. [Tools](#tools)
5. [Exploratory Data Analysis (EDA)](#eda)
6. [Data Cleaning Preparation](#data-cleaning-preparation)
7. [Results and Findings](#results-and-findings)
8. [Recommendations](#recommendations)
9. [Limitations](#limitations)
10. [References](#references)

## Overview
This project aims to provide a comprehensive analysis of criminal traffic statistics in Florida from 2011 to 2023. Through visualizations and insights derived from the data, we seek to offer a deeper understanding of trends, patterns, and implications regarding criminal traffic offenses in the state. By leveraging data visualization techniques and statistical analysis, we aim to empower stakeholders and the public with actionable insights to enhance road safety and reduce criminal traffic incidents.
## Objectives
The aim of this EDA is to gain insights into the distribution, trends, and patterns of criminal traffic citations in Florida from 2011 to 2023. The analysis focuses on three main aspects: Criminal Traffic Citations vs. Classification over the years, total citations over the years, and the breakdown of agencies who applied the citations over the years.
- **Trend Analysis**: Understand trends and patterns in Florida's housing market over time.
- **Relationship Exploration**: Explore the relationship between mortgage rates, housing inventory, and median listing prices in Florida.
- **Factor Identification**: Identify factors influencing fluctuations in housing inventory and prices in the state.
- **Recommendation Generation**: Provide recommendations for stakeholders based on analysis findings.

By achieving these objectives, the project aims to contribute to a better understanding of the dynamics driving the Florida housing market and provide valuable insights for decision-making in the real estate sector.
## Data Source

The primary data source for this project is the Florida Highway Safety and Motor Vehicles (FLHSMV) database, which contains comprehensive records of criminal traffic statistics spanning from 2011 to 2023. Additional sources may include government reports, academic studies, and other publicly available datasets related to road safety in Florida.
## Tools

The tools and technologies used in the project include:
- **Microsoft Excel**: Employed for manual data cleaning and preprocessing of individual XLS files downloaded for each year from 2011 to 2023. Excel functionalities such as sorting, filtering, and formula application facilitated tasks like handling missing values, standardizing data formats, removing duplicates, and ensuring consistency across datasets.
- **Tableau Public Desktop**: Utilized for data visualization and interactive dashboard creation. Tableau's intuitive interface enabled the exploration of cleaned datasets through various visualization techniques, including charts, graphs, maps, and dashboards. Interactivity features such as filters, parameters, and actions allowed for dynamic exploration and analysis of the data.
- **GitHub**: Version control and collaboration platform for storing project code and documentation.

By leveraging these tools and technologies, the project successfully conducted exploratory data analysis and created interactive visualizations to gain insights into the dynamics of Florida Criminal Traffic Citations Statistics from 2011 to 2023.
## Data Cleaning

Data cleaning in Microsoft Excel involved meticulous manual processes to ensure data accuracy and consistency. Tasks included:

Handling missing values: Identifying and filling in missing data points or removing incomplete records.
Standardizing data formats: Ensuring consistency in date formats, offense categories, and geographical identifiers.
Removing duplicates: Eliminating duplicate entries to maintain data integrity and avoid skewing analysis results.
Quality assurance: Verifying data accuracy and conducting sanity checks to identify any anomalies or inconsistencies.

By completing these data cleaning and preparation steps, we ensured that the datasets were accurate, consistent, and ready for in-depth analysis. These efforts set the stage for uncovering insights into the dynamics of of Florida Criminal Traffic Citations Statistics from 2011 to 2023.
## Exploratory Data Analysis (EDA) 

Exploratory Data Analysis (EDA) is conducted to understand trends, patterns, and relationships within the datasets. This includes data loading, summary statistics, data visualization, and key findings.
- **Loading and Inspection of Datasets:** The first step involved loading the datasets obtained from the Federal Reserve Economic Data (FRED) into our analysis environment. Each dataset was loaded into a Pandas DataFrame, allowing for efficient manipulation and exploration. We inspected the structure of the datasets, including column names, data types, and missing values, to ensure data integrity and consistency.
- **Data Visualization:** Visualization played a pivotal role in uncovering patterns and trends within the datasets. Various plots, including time series plots, histograms, and scatter plots, were created to visualize the relationships between variables and identify potential trends over time. Visualization allowed for a comprehensive exploration of the data and facilitated the identification of significant insights.
- **Key Findings:** The EDA revealed several key findings regarding the Florida housing market and the influence of mortgage rates on housing inventory and median listing prices:

Temporal Trends - Time series analysis showed temporal trends in median listing prices, mortgage rates, and housing inventory levels over the study period. Fluctuations and potential seasonal patterns were observed, providing insights into the cyclical nature of the Florida housing market.

Insights and Implications - Overall, the EDA provided valuable insights into the Florida housing market's dynamics and the relationships between key variables. 
## Results and Findings

- **Overall Decrease in Traffic Criminal Violations:** The analysis revealed a significant decrease of almost 30% in traffic criminal violations from 2011 to 2023 in Florida. This indicates positive progress in road safety practices and compliance with traffic laws over the analyzed period.
- **Influence of Specific Violation Types on the Trend:** Positive Trends: Certain violations, such as driving while license suspended or revoked, violation of driver license registration, and unlawful use of driver license, showed substantial decreases, contributing to the overall decline in violations. Negative Trends: However, there were concerning increases in reckless driving incidents by 30% and fleeing or attempting to elude a police officer by 55%, highlighting challenges in maintaining safe driving behaviors and enforcing traffic laws effectively.
- **Implications for Road Safety and Enforcement Strategies:** The findings suggest that while overall compliance with traffic laws has improved, there are persistent challenges in addressing reckless driving behaviors and evasion incidents.  Targeted enforcement measures, enhanced officer training, and public education campaigns are recommended to address rising trends in reckless driving and evasion incidents.  Refining pursuit policies, strengthening penalties for fleeing offenders, and enhancing collaboration between agencies are crucial for mitigating risks associated with high-speed pursuits and promoting public safety.
- **Importance of Data-Driven Decision Making:** Utilizing data analytics enables evidence-based decision-making and resource allocation. Continuous monitoring and evaluation of enforcement efforts are essential for adapting strategies and addressing emerging challenges effectively. Collaboration with community stakeholders and advocacy groups is vital for raising awareness, promoting responsible driving behaviors, and supporting enforcement efforts.
- **Recommendations for Policy and Action:** Policymakers and law enforcement agencies should prioritize resources and strategies to address the root causes of reckless driving and evasion incidents.  Strengthening collaboration between agencies, enhancing officer training, and leveraging technology for enforcement and public education are key strategies for improving road safety outcomes.  Continued investment in data collection, analysis, and monitoring is necessary to inform evidence-based policies and interventions aimed at reducing traffic violations and improving road safety for all road users.
- **Future Directions and Areas for Further Research:** Further research is warranted to explore the underlying factors contributing to the observed trends in traffic violations and to evaluate the effectiveness of enforcement measures and interventions in promoting road safety.  Longitudinal studies tracking changes in driver behavior and attitudes over time can provide insights into the evolving challenges and opportunities in traffic enforcement and road safety efforts.

In conclusion, the findings underscore the importance of ongoing efforts to address persistent challenges in traffic enforcement and promote a culture of responsible driving. By implementing evidence-based policies and collaborative strategies, stakeholders can work together to improve road safety outcomes and create safer roadways for communities across Florida.
## Recommendations
- **Enhanced Enforcement Strategies:** Implement targeted enforcement measures, including increased patrols, sobriety checkpoints, and speed enforcement, to address specific violation types such as reckless driving and driving under the influence (DUI).  Utilize data analytics and predictive modeling to identify high-risk areas and times for traffic violations, allowing law enforcement agencies to deploy resources effectively.
- **Public Awareness Campaigns:** Launch comprehensive public awareness campaigns highlighting the dangers of reckless driving, the consequences of traffic violations, and the importance of responsible driving behaviors.  Collaborate with community organizations, schools, and local businesses to disseminate educational materials and promote safe driving practices among motorists.
- **Policy Refinement and Collaboration:** Review and refine pursuit policies to ensure the safety of law enforcement officers, suspects, and bystanders during high-speed chases.  Strengthen penalties for fleeing or attempting to elude a police officer to deter offenders and enhance accountability for dangerous driving behaviors.  Foster collaboration between law enforcement agencies, government agencies, and community stakeholders to develop holistic solutions addressing underlying factors contributing to traffic violations.
- **Investment in Technology and Infrastructure:** Invest in technology solutions such as automated enforcement systems, traffic surveillance cameras, and vehicle safety technologies to enhance traffic monitoring and enforcement capabilities.  Improve roadway infrastructure, signage, and lighting to mitigate risks and improve visibility, reducing the likelihood of accidents and traffic violations.
## Limitations
- **Data Quality and Completeness:** The analysis relies on the availability and accuracy of data collected by law enforcement agencies, which may vary in quality and completeness.  Limitations in data collection methods and reporting practices may impact the reliability and consistency of findings, potentially leading to biases or inaccuracies in the analysis.
- **Scope and Generalizability:** The analysis focuses on traffic violations in Florida and may not be generalizable to other regions or jurisdictions with different traffic enforcement practices, demographics, and road infrastructure.  Findings may be influenced by unique factors specific to Florida, such as weather patterns, population demographics, and cultural norms, limiting the applicability of recommendations to other contexts.
- **Temporal Constraints:** The analysis covers a specific time period from 2011 to 2023, which may not capture longer-term trends or cyclical patterns in traffic violations.  Changes in enforcement strategies, legislation, and societal factors occurring outside the analyzed timeframe may not be accounted for in the analysis, affecting the interpretation of findings and recommendations.

Acknowledging these limitations is essential for providing a balanced and nuanced understanding of the analysis and its implications. Additionally, it can guide future research efforts and help refine the methodology for more robust findings.
## References
References to the datasets used in the analysis obtained from Florida Department of Highway Safety and Motor Vehicles (FLHSMV).
- Retrieved from FLHSMV, Florida Department of Highway Safety and Motor Vehicles; [Link](https://www.flhsmv.gov/)


