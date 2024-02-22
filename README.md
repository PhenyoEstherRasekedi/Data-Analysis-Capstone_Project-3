# Restaurant Rating Dashboard

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#resultsfindings)
- [Limitations](#limitations)

### Project Overview

This data analysis project aims to analyze and draw out meaningful insights from a customer survey of restaurants in some mexican cities to aid business entrepreneurs and investors in making more informed decisions.

**_Disclaimer_** : _All datasets and reports do not represent any company, institution or country, but just a dummy dataset to demonstrate capabilities of PowerBi._

### Data Sources

The 5 datasets used for this analysis are 'consumer_preferences.csv, 'consumers.csv', 'ratings.csv', 'restaurant_cuisines.csv' and 'restaurants.csv'. The datasets contain detailed information about the restaurants and various information about each customer from age to preferrences.

### Tools

- PowerBi
  - Data Cleaning
  - Data Modelling
  - Data Analysis
  - Creating Report

### Data Cleaning/ Preparation

In the intial data preparation phase, I performed the following tasks:

1. Data loading and inspection
2. Handling missing values
3. Data cleaning and formatting

### Exploratory Data Analysis

EDA involved exploring the customer survey data to answer key questions such as:

- What can you learn from the highest rated restaurants? Do consumer preferences have an effect on ratings?

- What are the consumer demographics? Does this indicate a bias in the data sample?

- Are there any demand & supply gaps that you can exploit in the market?

- If you were to invest in a restaurant, which characteristics would you be looking for?

### Data Analysis

The following PowerBi features were incorporated:

- Filters
- Modelling
- Interactive Slicers
- Power Query
- Conditional Column

### Results/Findings

The analysis results are summarized as follows:

1. The Top restaurant by number of orders is Tartosas Locas and the Top 3 restaurant by overall ratings is Las Mananitas.

| Restaurant    | Franchise | Smoking | Area   | Price  | AlcoholService | Cuisine       | Parking |
| ------------- | --------- | ------- | ------ | ------ | -------------- | ------------- | ------- |
| Tortas        | No        | No      | Closed | Medium | No             | FastFood      | Public  |
| Las Mananitas | No        | No      | Closed | High   | Wine&beer      | International | Yes     |

The common things about the top rated restaurants by overall ratings and orders is that they do not allow smoking, they are non-franchise establishments, located in closed areas with parking and mostly moderately priced.

Top Consumer preferences are;

| Cuisine | Franchise | Smoking | Area   | Budget | Drinking Level | Transport |
| ------- | --------- | ------- | ------ | ------ | -------------- | --------- |
| Mexican | No        | No      | Closed | Medium | Casual         | Public    |

Mexican food is the most preferred cuisine however, the top rated restaurants serve fast food, brewery, japanese and international cuisine. So evidently cuisine preferences do not have an effect on ratings in this aspect.

In terms of franchise, consumers mostly preffer non-franchise establishments and 3 of the 4 highest rated restaurants meet this preference which shows the effect on ratings.

86% of consumers are non-smokers and the effect of this preference on ratings is evident because all the top rated restaurants do not allow smoking. The same goes for closed areas as well.

The top restaurants being moderately priced reflects the data that 47% of consumers have a medium budget.

A majority of the consumers are casual, abstemious drinkers, this is reflected in the ratings as the top restaurants either do not serve alcohol or have a wine and beer menu.

62% of consumers use public transport so the top rated restaurants not having parking is not a deal breaker.

2. A majority of the consumers are single twenty year old students who do not have children, live in San Luis Potosi with a low-medium budget. They use public transport, do not smoke but are abstemious drinkers. This indicates a bias in the data sample as the restaurant they order from the most sells fast food at a medium price which is typical for students.

3. The top 3 restaurants by orders have low average service ratings therefore, offering quality customer service would garner loyalty and keep any competitor restaurant at the top.
   There is a 20% demand for smoking areas, a 35% demand for franchise restaurants and a 38% demand for open area restaurants

4. If I were to invest in a restaurant, I would invest in one with a closed area, public parking, moderately priced, wine and beer menu, no smoking, non-franchise that sells fast food to appeal to the student population.

To target the adult market, I would invest in a closed area non-franchise restaurant with a smoking section, wine and beer menu that sells mexican and international food at a medium price. It should have parking since a moajority of them have cars.

The quality of service and food served are also important as they should be excellent to in order to be competitive.

### Limitations

I grouped age 18-35 as youth, 36-50 as adult, 51-65 as senior, 65+ as elder.
I removed null/unanswered values from the results.
