# Side_side

Get the maximum and minimum of GDP per capita for all continents

What i did in Nutshell:

- Grouped data by continent
- Summarized the data based on minimum gdpPercap for each country
- Plotted normal table and one from knitr package (clearly knitr is much better so just used it from now on)
- Plotted a box plot  

Loading the libraries

```r
library(gapminder)
library(tidyverse)
```

<div class="twoC">

continent    min_gdPercap
----------  -------------
Africa           241.1659
Americas        1201.6372
Asia             331.0000
Europe           973.5332
Oceania        10039.5956

![](Side_side_files/figure-html/unnamed-chunk-2-1.png)<!-- -->

</div>
<div class="clearer"></div>

<style type="text/css">
.twoC {width: 100%}
.clearer {clear: both}
.twoC .table {max-width: 50%; float: right}
.twoC img {max-width: 50%; float: left}
</style>
