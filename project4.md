# Project 4
## Investigating Margins of Error
In general in this project, RStudio had difficulty running with so many large objects, which caused the program to crash often and delete my files. This forced me to have to restart R, my computer, and the project multiple times. I did manage to fully generate the plots for the project, though they are not in the highest resolution, since I took screenshots of the plots so as not to overload RStudio and cause it to crash again.
This part of the project involved predicting population counts for each gridcell of my country, Laos. Then I had to compare the predicted values with the actual values of Laos by looking at areas of the country where the predicted values seemed off (in more highly populated areas). The plots below show the difference in predicted and actual population counts for Vientiane prefecture and Savannakhét as well as the plot of actual population in the areas. Overall the difference did not seem that great, which suggests that the predicted values were extremely close to the actual values. While there may have been some error in my own code, I ran the program multiple times (with edits) and received similar results.
### Vientiane prefecture:
![](vientiane_plot2.png)
![](urban_pop2.png)
### Savannakhét:
* ![](urban2_diff.png)
* ![](urban2_pop.png)
## Investigating and Comparing results
### Response variable is population and the predictors are sum of covariates:
* ![](p2_pop_sums.png)
* ![](p2_diff_sums.png)
* ![](diff)
### Response variable is population and the predictors are mean of covariates:
* ![](p2_pop_means.png)
* ![](p2_diff_means.png)
* ![](diff2)
### Reponse variable is log of population and the predictors are mean of covariates:
* ![](p2_pop_logpop.png)
* ![](p2_diff_logpop.png)
* ![](diff3)
