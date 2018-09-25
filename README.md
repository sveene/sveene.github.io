Shiny Application & Reproducible Pitch Projects
========================================================
author: Veene
date: September 25, 2018
autosize: true

Reproducible Pitch 
========================================================

This presentation is done as part of the final course project for 'Developing Data Products' course in the Data Science Specialization track by John Hopkins University on Coursera.

The web application is hosted on the link below:

[Reproducible Pitch](https://sveene.neocities.org/Reproducible_Pitch.html)



Shiny Application - Choose your car
========================================================

The web application is hosted on the link below:

[Choose your car](https://sveene.shinyapps.io/ChooseYourCar/)


Application Overview
========================================================

This web application allows you to choose a car that suits your needs.

Enter the distance and price of gas and the application will show the cars having mpg in your suitable range.

Additionally, you can also choose some characteristics of the cars that you desire: Cylinders, Displacement, Horse Power and Transmission. 

Dataset Overview
========================================================

The application uses 'mtcars' dataset from the 'datasets' package in R which lists down 10 aspects of automobile design and performance for 32 cars.

```{r, echo=TRUE}
library(datasets)
data(mtcars)
head(mtcars, 4)

```

Variable Correlation
========================================================

```{r, echo=TRUE}
library(datasets)
data(mtcars)
cor(mtcars)
