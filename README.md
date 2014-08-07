# Demos of CRAN log plotting in R, R Markdown, and R Markdown + Shiny

## Prerequisites

- shiny
- knitr
- devtools
- dplyr
- ggplot2
- rmarkdown
- [RStudio](http://www.rstudio.com/products/rstudio/) v0.98.850 or higher

```r
install.packages(c("shiny", "knitr", "devtools", "dplyr", "ggplot2))
devtools::install_github("rstudio/rmarkdown")
```

## Files

- **daily.rds** - CRAN log data from cran.rstudio.com up to 08-04-2014
- **cranlogs.R** - Step through this R file to see an evolving series of plots
- **cranlogs1.Rmd** - Static R Markdown document; open in RStudio and click the "Knit HTML" button
- **cranlogs2.Rmd** - Interactive Shiny document; open in RStudio and click "Run document"

