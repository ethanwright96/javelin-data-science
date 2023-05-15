# javelin-data-science
# Exploratory Data Analysis of the Javelin Throw

1. What is the age distribution of professional javelin throwers? (both male and female)

Elite Men's Javelin Throwers

![alt text](https://github.com/ethanwright96/javelin-data-science/blob/main/World%20Athletics/Histogram_Men_Javelin.png)

![alt text](https://github.com/ethanwright96/javelin-data-science/blob/main/World%20Athletics/significant_pairwise_ttest_results_men_javelin.png)

1st Class Male Javelin Throwers: those ranked in the top 100 by World Athletics, have an average age that is statistically significantly different than that of all other classes of javelin throwers in the top 500. Average age of Male 1st Class Throwers is greater in all cases; ranging from 2.1 to 3.4 years older.

Elite Women's Javelin Throw

![alt text](https://github.com/ethanwright96/javelin-data-science/blob/main/World%20Athletics/Histogram_Women_Javelin.png)

![alt text](https://github.com/ethanwright96/javelin-data-science/blob/main/World%20Athletics/significant_pairwise_ttest_results_women_javelin.png)

Similarly, 1st Class Female Javelin Throwers: those ranked in the top 100 by World Athletics, have an average age that is statistically significantly different than that of all other classes of javelin throwers in the top 500. Average age of Female 1st Class Throwers is greater in all cases; ranging from 3.9 to 5.4 years older: a difference approximately 2 years more extreme than that observed between classes of Male throwers.



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
