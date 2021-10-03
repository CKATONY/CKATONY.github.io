Project 1 Blog
================
Jiatao Wang
10/2/2021

## What I have doen in this project

This project basically explored my current limited R knowledge by
accessing and querying API.Although I could not get all data from
pokeAPI. It is intriguing to obtain the data that I am interested in.
Those data really call back my memory while playing pokemon in
sp/psp(Game Boy/PlayStation Portable). Even though I could not
acknowlwdge most of the names in English. I did some basic exploratory
data analysis on the berry data set and analyzed some attributes. It is
interesting to find out that most of the berries grow pretty slow and
most of the berries are considered relevantly big. It seems that
firmness is not close related to the size of the berry.  
Some reflections:  
1. Berry is just a simple dataset without so many observations. It will
be a lot more fun to explore the pokemon species and some relationship
between the variables. 2. The most difficult part for me in the
beginning is how to obtain mostly useful information for different
endpoint. Because lots of endpoints are actually nested within each
endpoint. I took a pretty tedius way/time-consuming way to deal with
this API, there is definitely faster and efficient way to handle
restAPI. The logic is not a big problem for me. 3. I certainly need to
know some more powerful built in functions in order to save my time of
building those functions or the universal functions. But I consider my
project to be successful(even though the functions are not fast)

## Access

The link to the github pages repo is
[here](https://ckatony.github.io/ST558-Project-1-/)  
The link to the usual repo is
[here](https://github.com/CKATONY/ST558-Project-1-/tree/main)

``` r
rmarkdown::render("/Users/CKA/Documents/CKA/CKATONY.github.io/_Rmd/Project 1 Blog.Rmd", 
              output_format = "github_document", 
              output_dir = "/Users/CKA/Documents/CKA/CKATONY.github.io/_posts",
              output_options = list(
                keep_html = FALSE
                )
              )
```
