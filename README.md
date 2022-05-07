# San Francisco Rental Housing Analysis 

Using interactive visualizations and geospatial analysis, this program will find properties in the San Francisco Market that are viable investment opportunitites. Based on the visualizations, we will create a data story



## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://github.com/pandas-dev/pandas) - For DataFrame construction and data sorting.

* [hvplot](https://pyviz-dev.github.io/hvplot/user_guide/Introduction.html) - For data visualizations

---

## Installation Guide

Before running the application first install the following dependencies.


```python
  pip install pandas
  pip install hvplot
```

---



## Analysis

* What is the overall trend in housing_units over the period being analyzed?
    - The average amount of rented housing units increased each year between 2010-2016.

![Housing Units By Year](Images/zoomed-housing-units-by-year.png)



* Did any year experience a drop in the average sale price per square foot compared to the previous year? If so, did the gross rent increase or decrease during that year?
    - Sale price per square foot decreased from 2010 to 2011.
    - Gross rent increased in 2010.
![Sales Price Per Square Foot and Average Gross Rent](Images/avg-sale-px-sq-foot-gross-rent.png)



* For the Anza Vista neighborhood, is the average sale price per square foot for 2016 more or less than the price that’s listed for 2012?
    -  The 2016 average sale price for Anza Vista is less than the price listed for 2012.
![Sales Price Per Year and Average Gross Rent By Neighborhood](Images/pricing-info-by-neighborhood.png)



* Which neighborhood has the highest gross rent, and which has the highest sale price per square foot?
    - Westwood Park has the highest gross rent. Union Square has hte highest sale price per square foot.
![Interactive Map: Gross Rent By Neighborhood](Images/6-4-geoviews-plot.png)



* Data Story:
    - As rental income increases, sale prices remain mostly stable. For all neighborhoods, gross rent outpaced sales price per square foot. Neighborhoods with a steady sale price per square foot, or a sale price that decreases with respect to gross rent would be good investments. Hayes valley would be a good place to look at investment properties. The neighborhood's sales price is negatively correlated with average gross rent.

---
## Contributors


*  **Quintin Bland** <span>&nbsp;&nbsp;</span> |
<span>&nbsp;&nbsp;</span> *email:* quintinbland2@gmail.com <span>&nbsp;&nbsp;</span>|
<span>&nbsp;&nbsp;</span> [<img src="images/LI-In-Bug.png" alt="in" width="20"/>](https://www.linkedin.com/in/quintin-bland-a2b94310b/)

---

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
