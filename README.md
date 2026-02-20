# Nutrition_Project
Exploratory data analysis project of global nutrition data

I downloaded datasets from gapminder.org and who.int to investigate
- how the mean daily energy intake, mean sugar intake and mean household income per capita varies daily between countries
- how the percentage of population that is overweight varies between countries
- the relationship between all four variables

I firstly did some exploratory data analysis, where I looked at minimum, maximum, and mean values followed by plotting bar graphs to visualise some of these findings as well as boxplots to visualise the spread of the data and presence of outliers. I will also plot histograms to provide another method to visualise the data.

I lastly generated a correlation matrix heatmap, where I looked at the general correlation (Pearson's linear correlation) between all four variables. I will add interactive widgets which will permit graphical visualisations to compare the data between the chosen countries.

## Notes on the datasets

**food_supply_kilocalories_per_person_and_day.csv**
- Source: https://www.gapminder.org/data/
- Originally from: https://www.fao.org/faostat/en/#home
- Description: Mean daily energy intake per capita measured in kilocalories (kcal)

**sugar_per_person_g_per_day.csv**
- Source: https://www.gapminder.org/data/
- Originally from: https://www.fao.org/faostat/en/#home
- Description: Mean consumption of sugar and sweetners per capita measured in grams (g)

**mincpcap_cppp.csv**
- Source: https://www.gapminder.org/data/
- Originally from: World Bank
- Description: Mean daily household per capita income expressed in 2021 Purchasing Power Parity (constant international $)

**overweight.csv**
- Source: https://www.gapminder.org/data/](https://www.who.int/data/gho/data/indicators/indicator-details/GHO/prevalence-of-overweight-among-adults-bmi--25-(age-standardized-estimate)-(-))
- Originally from: N/A
- Description: Age-standardised estimate of the prevelance of adults that are overweight i.e. BMI >= 25 (%)
