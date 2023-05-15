# javelin-data-science
# Exploratory Data Analysis of the Javelin Throw

## Introduction
I embarked on my javelin throwing journey as a Freshman in High School, 12 years ago. What began as a commitment to learning the sport transformed into a relentless pursuit of technical excellence. Along the way, I achieved notable milestones, including clinching the Rhode Island High School State Championship title in 2014, setting several meet records, and garnering interest from UPenn, Cornell, and Brown University for recruitment. Ultimately, I chose Brown University, graduating in 2019.

Unfortunately, my college athletic career was cut short by a disc injury sustained while front-squatting. This setback compelled me to redirect my focus. I transitioned to a student-assistant coaching role for the javelin throw, channeling my energy into nurturing the skills of others. Additionally, I immersed myself in my other technical passion, the cello.

Over time, I embarked on a journey of recovery and self-strengthening. In 2015, I underwent stem cell therapy, followed by three years of refraining from high-impact activities. I dedicated myself to applied strength and conditioning, fortifying my body and mind. Today, I stand ready to make my comeback. Come Spring 2024, I will compete in the U.S. Men's Javelin circuit, resuming my athletic journey with renewed vigor. 

With a clear vision, mission, purpose, and platform, I dive into the captivating world of the javelin throw. As a micro-project, my aim is to investigate the spatial distribution, age-related disparities across genders and performance levels in track and field events, focusing on the Javelin Throw as a case study and experimental ground.

## Part I: Location

Display Choropleths here.

## Part II: Age 

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

## Part II: Progression

What sorts of classes might javelin throwers (and other event athletes) be placed/grouped in to better characterize age, performance, and longevity?

What is the spatial (international) distribution of Elite Javelin Throwers?

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
