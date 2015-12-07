
# Analysis of Diamonds Data
library(ggplot2);
library(knitr);


# Descriptive Analysis

```r
rows <- nrow(diamonds);
cols <- ncol(diamonds);
col.names <- colnames(diamonds);
```

This Diamonds Dataset contains 53940 records and 10 columns.

The names of columns are carat, cut, color, clarity, depth, table, price, x, y, z.


# 1st 6 Records of Dataset

```r
head(diamonds);
```

```
##   carat       cut color clarity depth table price    x    y    z
## 1  0.23     Ideal     E     SI2  61.5    55   326 3.95 3.98 2.43
## 2  0.21   Premium     E     SI1  59.8    61   326 3.89 3.84 2.31
## 3  0.23      Good     E     VS1  56.9    65   327 4.05 4.07 2.31
## 4  0.29   Premium     I     VS2  62.4    58   334 4.20 4.23 2.63
## 5  0.31      Good     J     SI2  63.3    58   335 4.34 4.35 2.75
## 6  0.24 Very Good     J    VVS2  62.8    57   336 3.94 3.96 2.48
```

# Last 6 Records of Dataset

```r
tail(diamonds);
```

```
##       carat       cut color clarity depth table price    x    y    z
## 53935  0.72   Premium     D     SI1  62.7    59  2757 5.69 5.73 3.58
## 53936  0.72     Ideal     D     SI1  60.8    57  2757 5.75 5.76 3.50
## 53937  0.72      Good     D     SI1  63.1    55  2757 5.69 5.75 3.61
## 53938  0.70 Very Good     D     SI1  62.8    60  2757 5.66 5.68 3.56
## 53939  0.86   Premium     H     SI2  61.0    58  2757 6.15 6.12 3.74
## 53940  0.75     Ideal     D     SI2  62.2    55  2757 5.83 5.87 3.64
```
