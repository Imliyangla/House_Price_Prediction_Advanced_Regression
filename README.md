# House Price Prediction using Advanced Regression
> Surprise Housing, a prominent US housing company, is strategically venturing into the Australian real estate market, leveraging data analytics to identify lucrative investment opportunities. The objective is to construct a robust regression model, employing regularization techniques like ridge and lasso regression. This model will discern significant variables influencing house prices and optimize investment decisions. The dataset, rich in details on house sales, enables a comprehensive analysis. By determining optimal regularization parameters, Surprise Housing aims for a data-driven market entry, focusing on areas with high returns. This initiative provides valuable insights into the pricing dynamics of the Australian real estate landscape.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- Background: The project stems from Surprise Housing's strategic expansion into the Australian real estate market, utilizing data analytics to optimize property investments.What is the background of your project?
- Business probem: To make efficient property investment by predicting house prices and understanding influential factors.
- Dataset used: The dataset, in CSV format, comprises comprehensive details on Australian house sales, including location, size, amenities, and condition, with the target variable being sale prices.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- EDA: After performing bivariate and multivariate EDA we saw some pattern in the trend of variables on Sale price as well as determined insignificant variables that were removed. 
- Lasso regression yeiled overall better results than simple linear regression and Ridge regression. 
- After employing Lasso regression:
   - The variables such as OverallQual, GrLivArea, GarageArea, TotalBsmtSF, CentralAir_Y, GarageType_Attchd, BsmtFinType1_GLQ, 1stFlrSF, BsmtFullBath, Foundation_PConc, - -  WoodDeckSF and MSZoning_RL `positively` affect the target variable `SalePrice` i.e the sale price goes higher.
   - On the other hand variables such as KitchenQual_TA, GarageFinish_Unf, ExterQual_TA, MSZoning_RM and FireplaceQu_none `negatively` affect the target variable `SalePrice` i.e. reduces the Sale price.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas - version 2.1.2
- numpy - version 1.26.1
- seaborn - version 0.13.0
- matplotlib - version 3.8.2
- sklearn - version 1.3.2


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- would like to thank UpGrad for giving us the oppurtunity to work on this project.


## Contact
Created by [Imliyangla](https://github.com/Imliyangla) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->