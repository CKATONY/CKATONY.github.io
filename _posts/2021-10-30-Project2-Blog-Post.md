Project 2 Blog
================
Jiatao Wang
10/30/2021

## Project Description

This project uses the automation to create several reports by changing
the parameters used in the code.  
The data set that is used in this project can be accessed
[here](https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity)  
Some Exploratory data analysis and supervised statistical learning
methods are applied to the data set.

## Access

The link for the usual repository on github is
[here](https://github.com/CKATONY/ST558-Project-2)  
The link for the github page repo is
[here](https://ckatony.github.io/ST558-Project-2/)

## What would you do differently?

I noticed that the even after taking the square root of test mean square
error, it is still a very large number. This result indicates that the
model fitting does not do so well. If more time is given, I will try to
do model selection using all the predictors(in this project, we fit the
model by selected predictors for the convenience of computation) (some
variables like LDA and weekday can be added to balance out the
variance). For the exploratory data analysis, there is definitely a lot
to do, we could do some principal component analysis. And there is a
time variable in the data set. It will be interesting to conduct some
time series analysis/multivariate analysis to see the if there is a
trend or not./stationary or not (Another way to forecasting the shares)

## what was the most difficult part for you?

I did a lot of online research on the automation: how to speed up random
forest/step function (replace the method = “rf” with method =
‘ranger’)  
The step function is actually not recommended since the number of
predictors in this data set is not small( and not too big ). Since it is
implemented by my partner, I tried some ways to deal with this
time-consuming method.(reduce the dimensions)

## what are your big take-aways from this project?

It is good to practice some other methods for predictive models and
write some function that will return your ideal result.  
Returning the model from best subset selection and using lasso
regression are good practices for me. Even though the automation part is
time-consuming, and we tried some parallel computing along the way, it
does not significantly improve the total time for the automation.

Finally, it is a good practice to explore what we can do with a data
set.

``` r
rmarkdown::render("/Users/CKA/Documents/CKA/project 2 repo/_Rmd/2021-10-30-Project2-Blog-Post.Rmd",
              output_format = "github_document", 
              output_dir = "/Users/CKA/Documents/CKA/project 2 repo/_posts",
              output_options = list(
                keep_html = FALSE
                )
              )
```
