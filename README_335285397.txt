# Dataset Overview
This small dataset spans from 2000 to 2023, covering food-related indicators for seven Asian countries: China, India, Indonesia, Japan, Jordan, Republic of Korea, and Singapore. The data sources include the Food and Agriculture Organization (FAO) and the United Nations (UN) database.

The dataset aims to evaluate whether people are eating "expensively" and whether their diets are "worth it" over time. It focuses on four key variables:

Prevalence of undernourishment (percent): Share of people not getting enough dietary energy.
Per capita food supply variability: Instability in daily per person food availability.
Average dietary energy requirement: Daily energy needed per person for a healthy life.
Consumer Price, Food Indices (2015 = 100): Food price changes over time, 2015 as baseline.

Together, these variables reflect the economic cost of food and the nutritional adequacy across different national contexts and development levels.


#Data Collection Method
The dataset primarily sources data from FAO and UN, while FAO and UN data are mainly sample-based because they rely on surveys conducted by member countries, such as household or agricultural surveys, rather than collecting data from every unit in the population. Therefore, the data in this dataset is sample data.


# Dataset Content Overview
The dataset's variables fall broadly into the following thematic groups:

Economic Cost – represented by food_price and price_volatility
Nutritional Adequacy – represented by calorie requirment,  food supply variability and undernourishment rate.


# Using the Dataset
You can use the dataset if you:

- Are exploring trends in food affordability and dietary quality in Asia.
- Want to analyze how economic development relates to food consumption patterns.
- Seek to visualize or model the relationship between price and nutrition.
- Need a compact dataset for classroom or capstone research on food systems.

#Limitations
Several potential issues might affect the accuracy and reliability of the data:

- Inconsistent national reporting standards – definitions and data collection methods may have changed over time within countries.

- Price calculation distortions – in some countries (e.g., China), the scope of "food" has shifted, sometimes including or excluding tobacco and alcohol. In China’s 2000 dataset, items like “tobacco” and “alcohol” were included under the general food category. In 2001, they were excluded, and by 2017, they were reported both jointly and separately—revealing changes in classification over time.

- Averaging bias – using yearly averages for food prices can overlook short-term shocks like natural disasters or seasonal fluctuations.


#Ethical Concrens
- Data interpretation bias – May reinforce stereotypes (e.g., assuming that high prices always mean better food or that certain countries "eat poorly").

- Cross-country comparison pitfalls – Economic and cultural differences may make comparisons seem judgmental or simplistic if not handled with care.

Does the dataset contain private or sensitive data?
No. All data are aggregate national-level statistics and do not involve any individual-level information.


# Notes
Missing Values:
Data for Singapore is missing for "Prevalence of undernourishment (percent) (3-year average)" and  "Per capita food supply variability (kcal/cap/day)" . A reasonable assumption is that Singapore's highly urbanized, high-income status and diversified food import system ensure a stable and sufficient supply, resulting in negligible undernourishment – potentially below FAO' s reporting threshold.

Derived Fields:
The method used to calculate annual food prices (by averaging monthly prices across countries excluding China) may be imprecise. It does not account for temporary but impactful disruptions like climate events, harvest failures, or policy shifts.


# Author and the date of release
Xingyu Wang(origin dataset from FAO, UN and China Statistical Yearbooks), 16/06/2025


