# Mchezopesa-Ltd

## Ojective

Come up with A Prediction result of a game between team 1 and team 2, based on

who's home and who's away, and on whether or not the game is

friendly (include rank in your training).

## Metrics of success

Making use of Ridge Regression to Use any three regressions learned this week to predict the rank of the teams and compare the models.

**What i came uo with**


**Summary**

To Chose and predict the rank of the teams Plus compare the models.

I decided to Use Ridge Regression,

**Model: Ridge Regression**


**What it is?**

Ridge regression is one of several regularized linear models. Regularization is the process of penalizing coefficients of variables either by removing them and or reduce their impact.

**TASK-DONE**

I had to identify the best parameters and best score, which came to about **0.209**
I checked for the RMSE score , it read **0.32**
Something to note, was that I realized the Rmse Score was higher than the best score,
This means the results are **cross-validated**. In addition, these results indicate that there is difference between the ridge and baseline models
This is True because it confirms whether a cross-validation was carried out or not


**As to which models I compared with?**

**I used Base line Model and Ridge Regresion Model**

BaseLine Gave me Results as Follows

**BaseLine Model**

away_score': 0.0007443505639096469,

 'away_team': 0.4999856456650823,
 
 'home_score': 7.665751624030825e-07,
 
 'home_team': 0.4999910235602645,
 
 'tournament': 0.0007386640707839463}
 
**Ridge Gave me Results as Follows**

Ride Regression Model

'away_score': -0.0020473948819355143,

 'away_team': 0.4954751988564855,
 
 'home_score': -0.000978994126995779,
 
 'home_team': 0.4954748854889723,
 
 'tournament': -0.0015380592926722446}
 

Finaly I carried out the Actual vs Predicted analysis Plus Rmse score
Rmse(root mean square error) checks for how accurately the Model Predicts

**Observation - Conclusion**
My MEAN score was **77(7.7)** and RMSE score was **44(4.4)**
Since my RMSE was Lower than mean, Which indicates a better fit and a Good Model

**Rmse(4.4) < Mean score(7.7) =  Good Model**
