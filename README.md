
<!-- README.md is generated from README.Rmd. Please edit that file -->
Funding Circle Dashboard
========================

[FC Dashboard](http://seabbs.co.uk/shiny/fcdashboard) ([alternative link](https://seabbs.shinyapps.io/fcdashboard/)) is a shiny application that allows exploratory data analysis of the [Funding Circle](https://www.fundingcircle.com) loanbook. It is not affiliated with Funding circle, the untransformed loanbook data is not provided.

Installing the shiny app locally
--------------------------------

To install and run the shiny app locally on your own computer you will need to first install [R](https://www.r-project.org/), it is also suggested that you install [Rstudio](https://www.rstudio.com/products/rstudio/download/). After downloading the source code from [this repository](https://www.github.com/seabbs/fcdashboard) click on the `fcdashboard.Rprof` file, this will open an Rstudio window. Type the following code into the command line;

``` r
install.packages("shiny")
install.packages("shinydashboard")
install.packages("shinyBS")
install.packages("tidyverse")
install.packagess("rmarkdown")
```

To run the app open the `ui.R` file and press run, depending on your computer this may take some time. Enjoy exploring the funding circle loanbook!
