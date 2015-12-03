Including R-language Code chunks and their Results in *.md files
================================================================
1. prepare a file with markup text and R-code chunks and store with extension **.Rmd**

2. by using **knit()** function of **knitr** package convert .Rmd file into .md file

```{r results="hide"}
library(knitr);

path = "c:/desktop";
setwd(path);

knit("Example02.Rmd");
```

it will create a file **Example02.md** file and a folder **figure** if your R-code chunk contains any plots. 

now **push** the file **Example02.md** and folder **figure** to **Central Repository** in GitHub

Note: Example files Example02.Rmd, Example02.md and corresponding folder **figure** you can find here
