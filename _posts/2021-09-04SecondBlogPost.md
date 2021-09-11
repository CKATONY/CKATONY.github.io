---
layout: post
title: ST558 Second Blog Post 
---
================
Jiatao Wang
9/3/2021

``` r
library(rmarkdown)
rmarkdown::render("/Users/CKA/Documents/CKA/CKATONY.github.io/_Rmd/2021-09-04SecondBlogPost.Rmd", 
              output_format = "github_document", 
              output_dir = "/Users/CKA/Documents/CKA/CKATONY.github.io/_posts",
              output_options = list(
                keep_html = FALSE
                )
              )
```

## Response

I think R is a pretty handy and powerful programming language. It could
manipulate data set using simple functions and those functions are
pretty easy to understand and to be remembered. I have used SAS Python
and SQL, putting SQL away, I think SAS have a more sophisticated
procedure to read data and do the data cleaning method, especially for
the unstructured dataset. But SAS is more powerful for doing statistical
analysis, the outputs produced by SAS have more interpretability.
Python, a more object oriented language, also have lots of advantage,
more easier to access API etc. I think R is not a difficult language to
learn as long as you have some programming background before. I learned
R prior to this course and I think there are lots of functions in R
really powerful and convenient for us to use. Such as some machine
learning techniques and statistical modeling. But sometimes R is pretty
slow comparing to Python.

## R Markdown Output

``` r
knitr::opts_chunk$set(fig.path = "../images/")
plot(iris3)
```

![](C:/Users/CKA/Documents/CKA/CKATONY.github.io/_posts/2021-09-04SecondBlogPost_files/figure-gfm/unnamed-chunk-3-1.png)<!-- -->
