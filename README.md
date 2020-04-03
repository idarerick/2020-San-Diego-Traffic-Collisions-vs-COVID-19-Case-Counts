# 2020 San Diego Traffic Collisions vs San Diego COVID-19 Case Counts

## Background

Having already noticed fewer cars on the road the week before the United States declared a state of emergency regarding the COVID-19 pandemic, I decided to chart a quick comparison of traffic in San Diego to the rising COVID-19 case counts in San Diego.

There were no datasets available that directly recorded the volume of traffic on San Diego roads so I used a dataset of [2020 reported traffic collisions](https://data.sandiego.gov/datasets/police-collisions/) as a measure of traffic in San Diego and daily maintained a dataset of confirmed COVID-19 cases by the [San Diego County Local Government](https://www.sandiegocounty.gov/content/sdc/hhsa/programs/phs/community_epidemiology/dc/2019-nCoV/status.html). My dataset can be found in the files in this repo as well as on a [kaggle link](https://www.kaggle.com/idarerick/san-diego-covid19-case-count).

The goal is to determine whether or not there is a correlation between the rising San Diego COVID-19 case counts in 2020 with reported traffic collisions in San Diego. The first visual includes a line graph that shows both the rising case counts of COVID-19 as well as falling number of reported traffic collisions. It is quite apparent that as the numbers rise, we see a significant dip in the reported traffic collisions.

![Traffic Collisions and COVID-19 Counts over Time](images/sd-traffic-collisions-vs-sd-covid-counts.png)

The second visual is a scatter regression of collisions vs COVID-19 case counts. As of April 1st, the R<sup>2</sup> is 0.511776.

![Collisions vs COVID-19 Regression](images/sd-traffic-collisions-vs-sd-covid-counts-regression.png)
