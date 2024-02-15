# Restaurant Rating Dashboard

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#resultsfindings)
- [Recommendations](#recommendations)

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

1. The Top 3 restaurants by orders are Cafeteria Y, Puesto De Tacos and Tartosas Locas. The Top 3 by overall ratings are Emillianos, Michiko and Las Mananitas.

| Restaurant    | Franchise | Smoking | Area   | Price  | AlcoholService | Cuisine       | Parking |
| ------------- | --------- | ------- | ------ | ------ | -------------- | ------------- | ------- |
| Tortas        | No        | No      | Closed | Medium | No             | FastFood      | Public  |
| Puesto        | No        | No      | Open   | Low    | No             | Mexican       | No      |
| CafeteriaY    | No        | Section | Closed | Medium | Wine&beer      | Cafeteria     | Public  |
| Emilianos     | Yes       | No      | Closed | Low    | Wine&beer      | Brewery       | No      |
| Michiko       | No        | No      | Closed | Medium | No             | Japanese      | No      |
| Las Mananitas | No        | No      | Closed | High   | Wine&beer      | International | Yes     |

Top Consumer preferences are;

| Cuisine   | Franchise | Smoking | Area   | Budget | Drinking Level | Transport | Rank |
| --------- | --------- | ------- | ------ | ------ | -------------- | --------- | ---- |
| Mexican   | No        | No      | Closed | Low    | Casual         | Public    | 1    |
| American  | Yes       | Yes     | Open   | Medium | Abstemious     | Car       | 2    |
| Cafeteria | Yes       | Yes     | Open   | High   | Social         | Foot      | 3    |

### Recommendations

### Limitations

I grouped age 18-35 as youth, 36-50 as adult, 51-65 as senior, 65+ as elder.
I removed null/unanswered values from the results.
