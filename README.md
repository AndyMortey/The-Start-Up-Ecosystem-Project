# The-Indian-Start-Up-Ecosystem-Project
## Introduction
This repository contains the code and resources for conducting an analysis of startup funding in India using the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework. The analysis aims to provide insights into the funding trends, top sectors, investor behavior, and geographical distribution of startup funding in India. CRISP-DM is a widely used methodology for conducting data mining or data analysis projects. It consists of six phases:
* Business understanding: understanding the needs of my team
* Data understanding: understanding the data and the expected information
* Data preparation: cleaning the data and formatting the data types
* Modelling: manipulating the data to draw insights
* Evaluation: assessing the results against the business objectives
* Deployment: presenting the findings.

## Project Scenario
My team is trying to venture into the Indian start-up ecosystem. As the data experts, we are to investigate the ecosystem and propose the best course of action.
* Analyze funding received by start-ups in India from 2018 to 2021.
* Separate data for each year of funding will be provided.
* In these datasets, you'll find the start-ups' details, the funding amounts received, and the investors' information.

## Business Understanding
The project begins with a comprehensive understanding of the business context, recognizing the importance of start-up funding dynamics for various stakeholders. Understanding the dynamics of start-up funding in India is crucial for investors seeking lucrative opportunities, entrepreneurs planning to launch new ventures, policymakers aiming to foster innovation, and researchers studying the evolving landscape. By analyzing funding trends, we aim to identify patterns, drivers, and key factors influencing investment decisions.

## Data Understanding
In this phase, we delve into gathering and preparing relevant datasets encompassing funding amounts, start-up names, industry sectors, and geographical locations. Explore the datasets to understand their structure, quality, and contents, identifying potential variables for analysis and visualization. Then perform summary statistics and distributions to gain insights into the data's characteristics and identify initial patterns or trends.

## Data Preparation
In this phase, data preprocessing techniques are applied to clean, integrate, and transform the raw data into a suitable format for analysis. This involves handling missing values, outliers, inconsistencies, standardizing data formats, ensuring the data is suitable for hypothesis testing and visualization. And performing feature engineering to extract pertinent features such as aggregating funding amounts by sector and creating categorical variables for visualization purposes. Finally, we integrate and merge datasets as needed to create a unified dataset for analysis, ensuring compatibility and consistency across variables. 

## Hypothesis Testing
The following hypotheses was formulated based on the business objectives and data exploration findings and was tested using ANOVA test.
* Null Hypothesis: The Sector a start-up belongs to has no significant impact on the funding amount it receives.
* Alternate Hypothesis: The Sector a start-up belongs to has a significant impact on the funding amount it receives.

## Answering Analytical Questions
These selected analytical questions were answered using visualizations.
* What is the total funding amount received by start-ups each year?
* Which ten start-ups received the most funding?
* Which ten start-ups received the least funding?
* Which ten sectors received the most funding?
* Which ten sectors received the least funding?
* How many start-ups got funded each year?

## Evaluation
This phase evaluates the results of the hypothesis test and insights derived from answers to some of the analytical questions and how they address the business objectives. The hypothesis test results shows the p-value (0.9997454509325898) is greater than the Significance value (0.05) hence, we fail to reject the null hypothesis. This means that our null hypothesis ('The Sector a start-up belongs to has no significant impact on the funding amount it receives') is correct. More information on some of the insights derived and recommendations is available in the jupyter notebook. 

## Deployment
Finally, the findings and insights are documented in the form of an article published on Medium and an interactive dashboard deployed in Power BI to facilitate exploration and dissemination of the results to a wider audience.

## Resources
* The article published on medium can be accessed via this link
* The Power Bi dashboard can also be accessed [here](https://app.powerbi.com/groups/me/reports/39344e30-1ecc-4f34-9ed2-37bbf498320a/ReportSection?experience=power-bi)

## Appreciation
I highly recommend Azubi Africa for their comprehensive and effective programs. Read More articles about [Azubi Africa here](https://medium.com/@azubiafrica) and take a few minutes to visit this link to learn more about Azubi Africa life-changing [programs](https://bit.ly/41CGCwK)

## Tags
[Azubi Data Science](https://bit.ly/3ARq742)




