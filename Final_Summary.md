## Final Summary

### Question 1: How do countries who compete only in summer differ from countries that compete in both seasons of Olympics?


### Chart 1: Participation mix by country, regression analysis
#### Northern Hemisphere Olympic Participation
#### Graph: Boxenplot of population by attendance category. Attendance category includes countries that attend both winter and summer olympics (=2), and countries that only attend summer games (=1).
#### Notes: The distribution of population for countries that attend both seasons is skewed, with the high population countries forming the tail. Boxplot display was confusing, with so many outliers. Boxenplot helps to visualize the skew of that distribution.
#### Observations: 
1. Countries that attend summer only have two characteristics:
* They are all close to the equator
* Their population is small, with little variance
2. Countries that participate in both have a wide range of populations, and include both small and the largest countries.  

![Participation mix by country](output/northern_output7.png)


### Chart 2: Participation mix by country, regression analysis
#### Northern Hemisphere Olympic Participation
#### Graph: Dotplot by latitude and percent of the country's athletes that attend summer olympics; only countries that attend both winter and summer olympics
#### Notes: The metric is the percent of their athletes that attent summer olympics. The purpose of the metric is to show the degree that a country sends more or less of their athletes to the winter or summer olympics.
#### Observations: 
1. For countries below 30 degrees latitude, (i.e. below the southern tip of Florida) participation in the winter olympics drops off considerably
2. In spite of the sharp, non-linear decline in the datapoints < 30 degrees latitude, the linear regression results are significant (p<.05).

![Participation mix by country](output/northern_output2.png)


### Question 2: Does the country’s latitude impact total number of medals won over time?

### Chart 1: Olympic Performance by Latitude: Summer
#### Northern Hemisphere Countries

#### Observations:
1. With the exception of the outlier, the USA, the majority of medal winning countries are above 30 degrees latitude and have won less than 7% of medals.
2. There is a very weak, positive correlation between latitude and medals won.

(output/summer-latitude performance.png)

