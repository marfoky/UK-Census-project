# UK-Census-project
Fundamentals of Data Science Census Project
Introduction
This project analyzes census data from a small town, named Middleburg, situated between two larger cities. The primary goal is to analyze the town’s demographic data and provide recommendations to the local government on how to best utilize an unoccupied plot of land and prioritize community investments. The analysis includes data pre-processing, population distribution, employment, religious affiliation, marital status, household distribution, commuting patterns, and birth and death rates.

Data Pre-processing
The dataset was preprocessed to handle missing data in several columns such as Relationship to Head of House, Marital Status, Infirmity, and Religion. Missing entries were replaced based on reasonable assumptions to maintain data integrity rather than using the biased mode imputation method. The preprocessed data consisted of 10016 rows and 11 columns, which were analyzed using Python and the Pandas library.

Handling Missing Data:
Relationship to Head of House: 597 missing values replaced with "Not Specified."
Marital Status: For individuals under 18, 2261 missing values replaced with "Not Applicable"; for those over 18, missing values replaced with "Not Specified."
Infirmity: 9935 missing values replaced with "Not Specified."
Religion: 5562 missing values replaced with "Not Specified."
Data Type Correction:
Age column: Converted from float to integer as only whole ages were relevant for the analysis.
Population Distribution
The population of Middleburg stands at 10,016, with 53% females and 47% males. The town’s population is divided into three age groups:

0-18 years: 24% of the population.
19-64 years: 63% of the population.
65+ years: 12% of the population.
The age distribution indicates a progressive structure with a high proportion of younger individuals, creating a demand for youth-oriented services and facilities.

Employment and Unemployment
91% employment rate: 9370 individuals are employed.
9% unemployment rate: 590 individuals are unemployed, notably higher than the UK's average. Common occupations include students, surgeons, textile designers, and researchers. The majority of the unemployed are within the 25-54 age range, highlighting the need for employment programs.
Religious Affiliation
55.54% of the population did not specify their religious affiliation. Among those who did, 23.22% identified as Christians, followed by Catholics (10.93%), and Methodists (7.32%). Minor religions include Muslims, Sikhs, and Buddhists, all representing less than 2%.

Marital Status
Marital status analysis reveals:

Married individuals: Predominantly aged 41-70.
Single individuals: Mostly in the 18-40 age range.
Household Distribution
The analysis identified 3,850 unique households, with an average household size of 2.6 people. Most households consist of single-occupant homes, which could be influenced by lifestyle preferences and demographic factors.

Commuting Patterns
Approximately 60% of the population commutes, consisting of university students and employed individuals. Non-commuters are those aged 65+, unemployed, or children.

Birth and Death Rates
Birth rate: A significant birth rate was observed, particularly among middle-aged women, suggesting future population growth and a need for more educational and recreational facilities.
Death rate: High mortality rates among the elderly (ages 66+), emphasizing the need for elderly care services.
Recommendations
1. Development on Unoccupied Land
Given the population trends and commuting patterns:

High-density housing: Recommended to accommodate the growing population efficiently.
Train station: To cater to the large commuting population, providing an alternative to road travel and boosting economic activity.
2. Investment in Community Services
The town’s high unemployment rate (9%) calls for:

Employment and training programs: To address the unemployment issue, especially for the 25-54 age range. This would improve job prospects, stimulate economic growth, and reduce dependency on social welfare.