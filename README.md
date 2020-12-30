# D_science_pj_01
This project is based of 'Data science job' salary prediction.
Salary data has been taken from glassdoor.com
Built 3 models Linear, Lasso, and Random Forest
Optimized them using GridsearchCV to reach the best model

Python Verson-3.8
Required Packages- pandas, numpy, sklearn, matplotlib, seaborn, json, pickle

## Data Parameter:

- job title
- Salary Estimate
- Job Description
- Rating
- Company Name
- Location
- Company Headquarters
- Company Size
- Company Founded Date
- Company Age
- Type of Ownership
- Industry
- Sector
- Revenue
- Competitors

## WordCloud:
![wordcloud](https://raw.githubusercontent.com/Istiaque-D-Omi/D_science_pj_01/main/wordcloud.png)

## Model Building:

- Splited the data in 80:20 for traing and testing.
- Built 3 models to get select the best model from.
- Evaluated them using Mean Absolute Error. Choose MAE because it is relatively easy to interpret and outliers weren’t particularly bad for this type of model.
- Multiple Linear Regression – Set Baseline for the model.
- Lasso Regression – Because of the sparse data from the many categorical variables, Normalized regression like lasso would be effective.
- Random Forest – With the sparsity associated with the data, This would be a good fit.

## Performance:
Random Forest model outperformed the other approaches on the test and validation sets.

-  ***Random Forest : MAE = 11.2***
-  ***Linear Regression: MAE = 18.8***
-  ***Lasso Regression :MAE =19.6***

