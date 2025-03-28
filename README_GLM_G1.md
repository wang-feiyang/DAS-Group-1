**Household Size Analysis using GLM**
**Overview**
This project is dedicated to analyzing the factors influencing household size. Utilizing data on demographic and housing characteristics, we aim to investigate how different household-related variables contribute to the number of people living in a household. By applying a Generalised Linear Model (GLM), we explore the statistical relationships between factors such as Engel’s coefficient, number of bedrooms, house age, and access to electricity, and their impact on household composition. The final model selection and interpretation provide data-driven insights to guide policy decisions on housing and social infrastructure.

**Data Source**
Datasets 1  are sourced from the Family Income and Expenditure Survey (FIES), conducted in the Philippines every three years. This nationwide survey is designed to collect detailed information on household income and spending patterns. Each of the five datasets represents a different region across the Philippines, offering a diverse view of household dynamics. The data is recorded at the household level, with several variables centered around the head of the household—defined as the individual recognized as being “in charge” of the home.



**Variables**
• Total.Household.Income – Annual household income (in Philippine peso)
• Region – The region of the Philippines which you have data for
• Total.Food.Expenditure – Annual expenditure by the household on food (in Philippine peso)
• Household.Head.Sex – Head of the households sex
• Household.Head.Age – Head of the households age (in years)
• Type.of.Household – Relationship between the group of people living in the house
• Total.Number.of.Family.members – Number of people living in the house
• House.Floor.Area – Floor area of the house (in 𝑚!)
• House.Age – Age of the building (in years)
• Number.of.bedrooms – Number of bedrooms in the house
• Electricity – Does the house have electricity? (1=Yes, 0=No)






**Methodology**
After completing data cleaning and preprocessing, we conducted exploratory data analysis (EDA) to understand the distribution and relationships within the dataset. 
We then applied Generalised Linear Models (GLM) to examine the impact of various household-related factors on the number of people living in a household. The response variable in our model is household size, 
treated as count data, making it well-suited for Poisson and Negative Binomial regression analysis.




**Repository Structure**
dataset01 1.csv: This directory contains the datasets used in the analysis.
Formal_Analysis.qmd: This directory contains the R scripts for the GLM analysis.
Plots: This directory will store the output of the analyses, including figures and tables.
README_GLM_G.md: Provides an overview and instructions for this repository.




**Getting Started**
To run the analysis, follow these steps:

Clone this repository to your local machine.
Make sure R and the necessary packages (tidyverse, MASS, etc.) are installed.
Run the scripts located in the /scripts directory.




**How to Contribute**

Contributions to this project are welcome! To contribute, please:

Fork the repository.
Create a new branch for your feature.
Add your feature or enhancement.
Submit a pull request.




**Contact**
For any questions or comments, please open an issue in this repository or contact the repository maintainer directly.
