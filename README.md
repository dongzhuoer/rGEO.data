# rGEO.data
[![Build Status](https://travis-ci.com/dongzhuoer/rGEO.data.svg?branch=master)](https://travis-ci.com/dongzhuoer/rGEO.data)



## Overview

This package include several data, and functions to create them. It serves as a 
    data package for rGEO.



## Install

```r
if (!('devtools' %in% .packages(T))) install.packages('devtools');
devtools::install_github('dongzhuoer/rGEO.data');
```



## develop

1. Refer to this [post](https://dongzhuoer.github.io/_redirects/develop-upon-my-r-package.html)



## to do

1. for `data-raw/GPL-html`, render individual .html to .rds, and use them as cache. Hope read 5000+ .rds and combind them can run quite fast.
1. for read_gpl_html(): when info is `NULL`, shouldn't read sample table (in this case you will read supplementary file table)

