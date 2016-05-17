
<!-- README.md is generated from README.Rmd. Please edit that file -->
About
=====

The goal of `saipeAPI` is to provide an R client for Census Bureau's API for Small Area Income and Poverty Estimates (SAIPE). Here is a short introduction for the SAIPE program from [Census](http://www.census.gov/data/developers/data-sets/Poverty-Statistics.html):

> The Small Area Income and Poverty Estimates (SAIPE) program produces single-year estimates of median household income and poverty for states and all counties, as well as population and poverty estimates for school districts. Since SAIPE estimates combine ACS data with administrative and other data, SAIPE estimates generally have lower variance than ACS estimates but are released later because they incorporate ACS data in the models. For counties and school districts, particularly those with populations below 65,000, the SAIPE program provides the most accurate subnational estimates of poverty. For counties, SAIPE generally provides the best single-year estimates of median household income.

Available Geographies
---------------------

SAIPE has four levels of income and poverty estimates: us, state, county, and school district.

Available Years
---------------

-   State and County: 1989, 1993, 1995-2014
-   School Districts: 1995, 1997, 1999-2014

Installation
============

``` r
# install.packages("devtools")
devtools::install_github("jjchern/saipeAPI")
```
