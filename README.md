# Hypothesis testing and power calculations app

...
## An R shiney app to conduct hypothesis testing and power calculations

...
### Description:

This project was a learning excersise using R-shiney which allows the user to use example data or their own data to conduct hypothesis testing and power calculations. 

The project consists of two main tabs:
* Normality and variance calculation
    * This tab accepts two numeric lists of data.
    * A histogram is automatically created.
    * Normality and variance tests are automatically conducted and displayed.
    * The user can manipulate the histogram bin size. This is upadted live on the histogram.
* Hypothesis testing and power calculation
    * This tave accepts two numeric lists of data.
    * The user can define which test they would like to use.
    * Once submitted, the mean and confidence intervals are shown for both samples and the test statistic. The p.value, power and ideal sample size is calculated and displayed.
    * Assumptions where necissary: alpha = 0.05, beta = 0.8, conf.level = 0.95

All tests are based on the work carried out in:
* Sultan et al., 2021 (https://doi.org/10.3389/fcell.2021.726281)

...
### Directory
* Statistics_app.R
    * A full self contained R-shiney app

...
### Installation and use:
A working example of the app can be found at:  https://samisultan.shinyapps.io/Statistical_app_2/

If the code has been cloned, ensure the dependencies have been installed below before running the R-shiney app within R-stuio.
More information can be found at: https://shiny.posit.co/r/getstarted/shiny-basics/lesson1/index.html 

...
### Dependencies
Created using R version 3.6.2 (2019-12-12)
```R
install.packages(c("shiny", "shinythemes", "MESS", "wmwpow", "WMWssp"))
```

...
### Contributions
Although contributions and comments are always welcome, please be aware that is project was used as a learning excersise and is not being activally maintained.

