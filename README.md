# Calculate your Rice GPA on a 4.0 scale

For unknown reasons, Rice uses A+ grades. These are going away in the near future, but in the meantime they make GPA calculations for grad school and job applications somewhat tedious.

This is a Shiny application that allows you to input your courses into a web interface and see your overall and major GPA, with the option of adjusting to a 4.0 scale.

The application is available [here](http://alexpghayes.shinyapps.io/rice_gpa). It's hosted for free and may take a while to load initially.

If have R and would like to run the application locally:

```r
install.packages(c("shiny", "tidyverse", "flexdashboard", "rhandsontable"))
rmarkdown::run("rice_gpa.Rmd")
```
