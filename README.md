# javelin-data-science
# Exploratory Data Analysis of the Javelin Throw

## Introduction

The purpose of this mini project was to use pandas to read HTML data from WorldAthletics.com to glean insights as to the age distribution among world-class javelin throwers.

## Part I: Age 

### 1. "How old is an average Javelin thrower?"

To gauge the average age of javelin throwers, various data sources can be utilized, ranging from High School Datasets like Milesplit to the Diamond League. For this analysis, I have chosen to utilize World Athletics' Rankings. World Athletics, formerly known as the International Association of Athletics Federations (IAAF), is the international governing body for track and field. They organize and oversee major athletics events worldwide, including the Olympic Games and World Championships (source: https://www.worldathletics.org/).

The World Athletics track and field rankings are determined using the World Athletics Ranking System, which considers an athlete's performance in specific events and assigns points based on the quality of their performance and the level of competition. By analyzing the current World Athletics Rankings, specifically focusing on the top 500-ranked javelin throwers globally, we can gain valuable insights and ask meaningful questions about the relationship between age, sport, and performance excellence.

The following analyses presented below utilize this dataset as a starting point to explore the dynamics between age and performance in javelin throwing.   

### Elite Men's Javelin Throwers

![alt text](https://github.com/ethanwright96/javelin-data-science/blob/main/World%20Athletics/Histogram_Men_Javelin.png)

<p align="center">
  <img src="https://github.com/ethanwright96/javelin-data-science/blob/main/World%20Athletics/significant_pairwise_ttest_results_men_javelin.png" alt="Pairwise T-Test Results" style="border: 1px solid black;">
</p>

First-Class Male Javelin Throwers, specifically those ranked in the top 100 by World Athletics, exhibit a statistically significant difference in average age compared to all other classes of javelin throwers within the top 500 rankings. On average, Male First-Class Throwers are older in all cases, with an age difference ranging from 2.1 to 3.4 years.

### Elite Women's Javelin Throw

![alt text](https://github.com/ethanwright96/javelin-data-science/blob/main/World%20Athletics/Histogram_Women_Javelin.png)
<p align="center">
  <img src="https://github.com/ethanwright96/javelin-data-science/blob/main/World%20Athletics/significant_pairwise_ttest_results_women_javelin.png" alt="Pairwise T-Test Results" style="border: 1px solid black;">
</p>
Likewise, First-Class Female Javelin Throwers, specifically those ranked in the top 100 by World Athletics, demonstrate a statistically significant difference in average age compared to all other classes of javelin throwers within the top 500 rankings. On average, Female First-Class Throwers are older in all cases, with an age difference ranging from 3.9 to 5.4 years. This difference is approximately 2 years more pronounced than the observed age difference between classes of Male throwers.
