# Credit Card Default Prediction

### Description
The goal of this project is to predict the defaults of credit card owners. I used logistic regression to build the model.  In addition, I used gridsearch to optimize the parameters of the model and used lasso to penalize certain coefficients.

### Dataset

The datasets utilizes a binary variable, default on payment (Yes = 1, No = 0) in column 24, as the response variable. There are 23 features in this set: 

* 1 Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit. 
* 2 Gender (1 = male; 2 = female). 
* 3 Education (1 = graduate school; 2 = university; 3 = high school; 4 = others). 
* 4 Marital status (1 = married; 2 = single; 3 = others). 
* 5 Age (year). 
* 6 = the repayment status in September, 2005
* 7:11 = the repayment status in August, 2005; . . .;X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above. 
* 12 = amount of bill statement in September, 2005; 
* 13 = amount of bill statement in August, 2005; . . .; X17 = amount of bill statement in April, 2005. 
* 18 = amount paid in September, 2005
* 19 = amount paid in August, 2005
* 20 = amount paid in July, 2005
* 21 = amount paid in June, 2005
* 22 = amount paid in May, 2005
* 23 = amount paid in April, 2005