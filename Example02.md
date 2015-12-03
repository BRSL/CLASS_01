# R Language code in Markdown file

![Image](images/Git.png)

## Analysis of iris data

iris is a predefined dataset in R langauge. We can use it directly.  
It contains data of three flowers:  
1. setosa  
2. versicolor  
3. verginica

There are FOUR numeric columns  
+ Petal.Length  
+ Petal.Width  
+ Sepal.Width  
+ Sepal.Length  


```r
data(iris);
head(iris);
```

```
#   Sepal.Length Sepal.Width Petal.Length Petal.Width Species
# 1          5.1         3.5          1.4         0.2  setosa
# 2          4.9         3.0          1.4         0.2  setosa
# 3          4.7         3.2          1.3         0.2  setosa
# 4          4.6         3.1          1.5         0.2  setosa
# 5          5.0         3.6          1.4         0.2  setosa
# 6          5.4         3.9          1.7         0.4  setosa
```

```r
tail(iris);
```

```
#     Sepal.Length Sepal.Width Petal.Length Petal.Width   Species
# 145          6.7         3.3          5.7         2.5 virginica
# 146          6.7         3.0          5.2         2.3 virginica
# 147          6.3         2.5          5.0         1.9 virginica
# 148          6.5         3.0          5.2         2.0 virginica
# 149          6.2         3.4          5.4         2.3 virginica
# 150          5.9         3.0          5.1         1.8 virginica
```

### Columns name of iris  

```
## [1] "Sepal.Length" "Sepal.Width"  "Petal.Length" "Petal.Width" 
## [5] "Species"
```

### Number of rows and Columns  
Rows are 150 and Columns are 5

### Data Visualization  

```r
barplot(1:10);
```

![plot of chunk plots](figure/plots-1.png) 

```r
plot(iris, col=1:3);
```

![plot of chunk plots](figure/plots-2.png) 


