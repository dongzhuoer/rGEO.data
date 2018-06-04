# rGEO.data

## Overview

big data files for rGEO

## to do

1. for `data-raw/GPL-html`, render individual .html to .rds, and use them as cache. Hope read 5000+ .rds and combind them can run quite fast.


## Install

```r
if (!('devtools' %in% .packages(T))) install.packages('devtools');
devtools::install_github('dongzhuoer/rGEO.data');
```

## develop

1. Refer to this [post](https://dongzhuoer.github.io/_redirects/develop-upon-my-r-package.html)
1. you may need `devtools::use_readme_rmd()` for the git "pre-commit" hook

```r
devtools::install_github('dongzhuoer/rGEO')
```
