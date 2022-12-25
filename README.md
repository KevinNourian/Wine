![Alt_Text](https://github.com/KevinNourian/Red-Wine/blob/main/Images/Wine.PNG)

# Introduction
Red wine is an alcoholic beverage made by fermenting the juice of dark-skinned grapes. Alcohol occurs when yeast converts the sugar in grapes into ethanol. The alcohol content in red wine usually ranges from 12% to 15%. In this report, I analyzed nearly 1,600 data points related to red Portuguese "Vinho Verde" wines. Each data point consists of 12 features. Each feature, except "quality," is an objective measurement. The quality scores -- between 3 and 8 -- were given by human testers. It is not clear what were the exact criteria for each score. The goals of this analysis are listed below.

# Goal
1. Determine if any set of features would more likely result in a human tester giving the wine a score of 7 or 8.
2. Determine which combination of features would determine the alcohol content of the wine.

# Technical Requirements
1. Perform exploratory data analysis.
2. Do hypothesis testing.
3. Apply machine learning models.
4. Provide clear explanations.
5. Provide conclusions and suggestions about how the analysis can be improved.

# Datasets
The dataset I used in this report is the Red Wine Quality dataset from Kaggle.

# Conclusions
**This Analysis:** I reviewed nearly 1,600 data points of red Portuguese "Vinho Verde" wines.
**Multivariant Logistic Regression Model to Predict Quality:** The logistic regression model I tested in this report used 7 features. It predicted quality with an ADEQUATE accuracy score of 0.78. <br>
**Multivariant Decision Tree Model to Predict Quality:** The decision tree model I tested in this report used 7 features. It predicted quality with an ADEQUATE accuracy score of 0.79. <br>
**Multivariant Linear Regression Model to Predict Alcohol:** The linear regression model I tested in this report used 6 features. It predicted alcohol with an INADEQUATE R-Squared value of 0.44 and an INADEQUATE adjusted R-Squared value of 0.39. <br>
**Overall Conclusion:** This analysis seems to indicate that it is possible to adequately predict the quality values from other data in this dataset but it is not possible to adequately predict the alcohol values from the data in this dataset. <br>
