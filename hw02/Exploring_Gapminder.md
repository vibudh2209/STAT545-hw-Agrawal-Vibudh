Exploring Gapminder
================

Loading the libraries

``` r
library(gapminder)
library(tidyverse)
```

Q1) What type is gapminder?

``` r
typeof(gapminder)
```

    ## [1] "list"

Q2) What is the class on gapminder

``` r
class(gapminder)
```

    ## [1] "tbl_df"     "tbl"        "data.frame"

Q3) How many variables/columns?

``` r
print("Coloumn equal to:")
```

    ## [1] "Coloumn equal to:"

``` r
ncol(gapminder)
```

    ## [1] 6

Q4) How many rows/observations?

``` r
print("Rows equal to:")
```

    ## [1] "Rows equal to:"

``` r
nrow(gapminder)
```

    ## [1] 1704

Q5) Can you get these facts about “extent” or “size” in more than one way? Can you imagine different functions being useful in different contexts?

``` r
#way 1 using dim command
print("way 1 using dim command")
```

    ## [1] "way 1 using dim command"

``` r
print("Rows equal to:")
```

    ## [1] "Rows equal to:"

``` r
dim(gapminder)[1] #Rows
```

    ## [1] 1704

``` r
print("Coloumn equal to:")
```

    ## [1] "Coloumn equal to:"

``` r
dim(gapminder)[2]
```

    ## [1] 6

``` r
#way two using length and transpose command
print("way two using length and transpose command")
```

    ## [1] "way two using length and transpose command"

``` r
print("Rows equal to:")
```

    ## [1] "Rows equal to:"

``` r
length(transpose(gapminder))
```

    ## [1] 1704

``` r
print("Coloumn equal to:")
```

    ## [1] "Coloumn equal to:"

``` r
length(gapminder)
```

    ## [1] 6

Q6) What data type is each variable?

``` r
sapply(gapminder,typeof)
```

    ##   country continent      year   lifeExp       pop gdpPercap 
    ## "integer" "integer" "integer"  "double" "integer"  "double"
