# python_data_analysis
This is a project work to demostrate Python Data Analysis skills.

### Evolution of obesity rates in United States, over the last decade

Obesity is a common, serious, and costly disease. Obesity-related conditions include heart disease, stroke, type 2 diabetes and certain types of cancer. These are among the leading causes of preventable, premature death. The estimated annual medical cost of obesity in the United States was nearly 173 billion in 2019 dollars. Medical costs for adults who had obesity were $1,861 higher than medical costs for people with healthy weight.

In this project we will explore Nutrition, Physical Activity, and Obesity - Behavioral Risk Factor Surveillance System data. We will also explore whether there is a strong correlation between obesity and age, gender, race, income and how these trends vary across United States.

About Data: This dataset includes data on adult's diet, physical activity, and weight status from Behavioral Risk Factor Surveillance System. This data is used for DNPAO's Data, Trends, and Maps database, which provides national and state specific data on obesity, nutrition, physical activity, and breastfeeding. https://chronicdata.cdc.gov/Nutrition-Physical-Activity-and-Obesity/Nutrition-Physical-Activity-and-Obesity-Behavioral/hn4x-zwk7

Updated: December 7, 2021

Data Provided by: Centers for Disease Control and Prevention (CDC), National Center for Chronic Disease Prevention and Health Promotion, Division of Nutrition, Physical Activity, and Obesity

### Please see Data_Clean_Up notebook for data cleaning/processing.
### Please see Project-Obesity-Analysis notebook for the conclusions.


### Research Questions
1. Which state has highest precentage of obese adult population?
2. Are there any state and national trends related to obesity in adults? 
3. Are there differences in obesity rates across Gender, Age, Race, Income and Education?
4. Do low levels of exercise and poor nutrition correlate with higher levels of obesity?

### Conclusions

1. For the last 2 years (2019, 2020) Mississippi had the highest rates of obesity in United States. We also see West Virginia and Louisiana appear on the list a few times.


2. Over the last decade (2011-2020), the USA obesity rates have gone up from 27.4% to 31.9%
 * Over the last decade (2011-2020), the state level obesity rates have gone up as well. In 2020, the state level chart confirms that the highest obesity rates were in Mississippi, West Virginia was a close second, followed by Alabama. Aggregating the data to regional level shows that the East South Central region shows highest obesity rates followed by the West South Central region. The East South Central region also showed the largest change (~20%) in obesity rates since 2011, from 31.7% to 38%
 * The high obesity rates are concentrated in the south central region. The lowest obesity rates appear to be in Colorado and Massachusetts.


3. There are significant differences across Gender, Race, Age, Income and Education levels:
 * The male obesity rates were higher till 2017, however the female obesity rates accelerated and are now higher than male obesity rates. In 2020, Female Obesity rates were 32.1% compared to Male obesity rates of 31.7%. This may require further research.
 * In 2020, the obesity rates are highest among age 45 to 54: 38.1%. The lowest obesity rates (19.5%) were in the age group 18 to 24 years. However, this younger group grew from 15.2% in 2011 to 19.5% in 2020. This is a concerning trend. 
 * Black population showed the highest rates of obesity, 41.6%, in 2020, which is more than 3.5x compared to Asian population obesity rates of 11.8%.
 * Lower income levels correlates with higher obesity rates. In 2020, population earning higher than 75,000 dollars showed the lowest levels of obesity rates, at 29% vs 37.9% for the population earning less than 15,000 dollars.
 * Lower levels of education correlates with higher obesity rates. In 2020, the population with less than a high school diploma shows obesity rates of 38.8% compared to 25% for college graduates.


4. Higher percentage of inactive population correlates with higher obesity rates and poor nutrition correlates with higher obesity rates:
 * Mississippi showed a higher percentage of inactive population. We see some noise in data, for example the data from Puerto Rico shows higher rates of inactiveness does not strongly correlate with higher obesity rates. 
 * Higher levels of fruit deficiency shows stronger correlation with higher rates of obesity. However, the relationship is less strong for vegetables deficiency. Also, some data points such as Puerto Rico are introducing noise in data, for example removing the data from Puerto Rico shows that obesity rates are not correlated with Vegetable deficiency rates.

**GitHub:** https://github.com/nsharma73/python_data_analysis