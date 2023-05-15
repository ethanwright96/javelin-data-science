# javelin-data-science
# Exploratory Data Analysis of the Javelin Throw

1. What is the age distribution of professional javelin throwers? (both male and female)

Elite Men's Javelin Throwers

![alt text](https://github.com/ethanwright96/javelin-data-science/blob/main/World%20Athletics/Histogram_Men_Javelin.png)

<p align="center">
  <img src="https://github.com/ethanwright96/javelin-data-science/blob/main/World%20Athletics/significant_pairwise_ttest_results_men_javelin.png" alt="Pairwise T-Test Results" style="border: 1px solid black;">
</p>

First-Class Male Javelin Throwers, specifically those ranked in the top 100 by World Athletics, exhibit a statistically significant difference in average age compared to all other classes of javelin throwers within the top 500 rankings. On average, Male First-Class Throwers are older in all cases, with an age difference ranging from 2.1 to 3.4 years.

Elite Women's Javelin Throw

![alt text](https://github.com/ethanwright96/javelin-data-science/blob/main/World%20Athletics/Histogram_Women_Javelin.png)
<p align="center">
  <img src="https://github.com/ethanwright96/javelin-data-science/blob/main/World%20Athletics/significant_pairwise_ttest_results_women_javelin.png" alt="Pairwise T-Test Results" style="border: 1px solid black;">
</p>
Likewise, First-Class Female Javelin Throwers, specifically those ranked in the top 100 by World Athletics, demonstrate a statistically significant difference in average age compared to all other classes of javelin throwers within the top 500 rankings. On average, Female First-Class Throwers are older in all cases, with an age difference ranging from 3.9 to 5.4 years. This difference is approximately 2 years more pronounced than the observed age difference between classes of Male throwers.


2. What are the summary statistics of these distributions?

3. What sorts of classes might javelin throwers (and other event athletes) be placed/grouped in to better characterize age, performance, and longevity?

4. What is the spatial (international) distribution of Elite Javelin Throwers?

Variables:

1. Date of Birth (for Age)

2. World Athletics Ranking

Question: How are World Athletics Rankings Calculated?

3. Personal Best (meters)

4. Season's Best (meters)

Candidate Classiers:

1. Excellence (PB x n International Competitions...)

2. Improvement (Slope of Seasons Bests over Time)

3. Consistency (Intra-competition, Inter-competition over Time)

4. Longevity (n years in x class)

5. Resilience (% PB post injury)

Potential Data Sources:

1. https://worldathletics.org/

2. Diamond League

3. World Championships

3. https://olympics.com/en/
