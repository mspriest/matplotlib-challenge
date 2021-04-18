# matplotlib-challenge
Unit 5 Matplotlib Homework: Pymaceuticals 

**<u>Background:</u>**

While your data companions rushed off to jobs in finance and government, you remained adamant that science was the way for you. Staying true to your mission, you've joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

**<u>Objective:</u>**

Provide top-level summary of the results based on tables and figures generated from data in two CSV files located in the data folder (Mouse_metada.csv and Study_results.csv) using Pandas, Scipy and Numpy libraries and Matplotlib to create charts.

**<u>Observations and Insights:</u>**

1. Nearly equal gender distribution suggests no correlation between gender and drug regimen effectiveness.
2. Capomulin and Ramicane were effective regimens based on the average tumor volume measurement at the final timepoints (32-40mm³ and 31-40mm³ respectively). Infubinol and Ceftamin regimens were not as effective (52-63mm³ and 47-62mm³ respectively).
3. For Mouse s185, the Capomulin regimen shrunk the tumor volume from 45mm³ to 22mm³ by its timepoint (45 days).
4. The scatter plot along with the correlation coefficient (.71)  suggests a relationship between mouse weight and tumor volume - the  heavier the mouse, the larger the tumor.