# Covid2019_project

This study was done in Collaboration with [![Destinee Maldonado](https://img.shields.io/badge/Destinee%20Maldonado-green?style=for-the-badge&logo=github)](https://github.com/dest072595)




## Abstract

This study investigates the intricate relationship between age, comorbidities, and COVID-19 mortality rates across the United States by leveraging multiple regression models. Utilizing extensive datasets from the National Center for Health Statistics, we executed a comprehensive exploratory data analysis followed by predictive modeling to discern patterns and predict mortality risks. Our research delves into the role of age and comorbidities as the determinant factors in COVID-19 mortality, where findings indicate a heightened risk associated with increased age, supported by statistical models across all states except Maine and Vermont. The study employs Lasso, Linear, and Logistic Regression techniques, with Principal Component Analysis (PCA) further refining the model's accuracy by addressing multicollinearity and enhancing feature selection. The results demonstrate that while Logistic Regression models yield high accuracy, the potential for overfitting is noted, emphasizing the importance of cross-validation in model assessment. Our findings offer valuable insights
 
for policymakers and healthcare providers, emphasizing the need for targeted public health interventions to protect vulnerable age groups. Additionally, we propose future research to examine the temporal progression of the pandemic through longitudinal data analysis, which could reveal more nuanced age-related mortality trends. This research not only contributes to the current understanding of the pandemic's demographic impact but also guides evidence-based policy-making for future public health challenges.


`graduate_PROJECT_ipynb` - Jupyter Notebook containing Covid-19 project.


## /Grad_project_datasets:  
1. `Conditions_Contributing_to_COVID-19_Deaths__by_State_and_Age__Provisional_2020-2023_20231016.csv` 

2. `Provisional_COVID-19_Deaths_by_Sex_and_Age_20231016`. 

Both of these datasets were procured from the National Institute of Health, meticulously created by the National Center for Health Statistics from the Division of Vital Statistics. They span data collated from 1/1/2020 to 9/27/2023. These are very large data sets, the first being 62100 rows (data points) by 14 columns (features) and the second being 13770 rows by 16 columns. These datasets are comprehensive, documenting information ranging from the specific start and end dates of data collection across almost four years of data, year and month of entry, state details, age groups, gender specifics, to granular data about COVID-19-related deaths and deaths from other conditions or comorbidities, like Pneumonia and Influenza. Central to our inquiry are questions surrounding the discernible patterns of age-related COVID-19 mortality across states and the potential to predict the likelihood of such mortality based on age


### Dataset Note:  
**Download** the datasets from the CDC in  `/Grad_project_datasets` folder
