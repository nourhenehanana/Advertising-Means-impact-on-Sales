# Advertising-Means-impact-on-Sales
This repository includes exploratory data analysis on advertising data to study the impact of the advertising means on the sales.

# Problem statement: 
The advertising dataset captures the sales revenue generated with respect ot advertisement costs across multiple channels loike radio, tv and newspapers.
In this little project, we use the linear regression to understand how spending on advertisements impact sales.
The questions below will guide us to reveal informations from the data: 

1/ Is there a relationship between ads and sales? 

2/ If so, how strong is that relationship?

3/ What types of ads contribute to sales ? 

4/ What is the effect each ad type has on sales? 

5/ Given ad spending, can sales be predicted ? 

# Result of the analysis

Tv and Radio have significant P values whereas newspaper does not, we reject the null hypothesis for TV and radio . There is no association between these fearures and sales.
We fail to reject the null hypothesis for the variable newspaper.
Tv and radios are positivly associated to sales
Newspaper ad spending is slightly negatively associated with sales
This ios relevent since we rejected the null hypothesis for the variable newspaper
The model has a higher R squared value compared to the previous model which means that this model provides a better fit to the data than a model that only includes the TV variable

- The linear regression done on the feature TV has an RMSE equal to 0.61.
- The multiple regression done on the 3 features has an RMSE equal to 0.86. 

'''feature selection: how do we know what features need to be included in a linear model'''
1/ try different models
2/ keep the predictores in the model if they have small p values
2/ check whether the R squared value goes up when we add new predictors

R square will always increase as we add more features to the model even if they are unrelated to the responsethus selecting the model with the highest R squared is not a reliable approach for choosing the best linear model.
Handling categorical predictors with two categories 

# How to interpret the results after doing the final multiple regression?
-considering all the other variables as fixed being in a suburban ares associated with an average decrease in sales of 106.56 widgets as compared to the baseline level which is rural
-wheras being in urban  area, associated with an average increase of sales of 268.13 widgets as compared to rural 
