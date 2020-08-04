Report on Gun Murders
================
Rafael Irizarry
2020-08-03

## Introduction

This is a report on 2010 gun murder rates obtained from FBI reports. The
original data was obtained from [this Wikipedia
page](https://en.wikipedia.org/wiki/Murder_in_the_United_States_by_state).

We are going to use the following library:

``` r
library(tidyverse)
```

and load the data we already wrangled:

``` r
load("rda/murders.rda")
```

\#Casey: this line above didn’t work following the original download
because the professor’s directory is different than mine, so I had to
edit it to match my directory to get it to work

## Murder rate by state

We note the large state to state variability by generating a barplot
showing the murder rate by state:

![](knit_test_files/figure-gfm/murder-rate-by-state-1.png)<!-- -->
