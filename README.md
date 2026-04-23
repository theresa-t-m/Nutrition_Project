# Nutrition_Project
Exploratory data analysis project of global nutrition data

I downloaded datasets from gapminder.org and who.int to investigate:
- how the mean daily energy intake, mean sugar intake and mean household income per capita varies daily between countries
- how the percentage of population that is overweight varies between countries
- the relationship between all four variables

In my Jupyter Notebook, I firstly did some exploratory data analysis where I looked at minimum, maximum, and mean values. I then generated bar graphs to visualise some of these findings as well as boxplots to visualise the spread of the data and presence of outliers. I will also plot histograms to provide another method to visualise the spread of the data.

I lastly generated a correlation matrix heatmap, where I looked at the general correlation (Pearson's linear correlation) between all four variables.

# Tableau Dashboard

The dashboard uses the datasets I had cleaned using Python. I have displayed a few interesting graphs and statistics.


<div class='tableauPlaceholder' id='viz1776964688346' style='position: relative'><noscript><a href='#'><img alt='Official ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ho&#47;HowOverweightistheWorld&#47;Official&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='HowOverweightistheWorld&#47;Official' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ho&#47;HowOverweightistheWorld&#47;Official&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1776964688346');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1300px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1300px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='5177px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

## Key Insights

# Notes on the datasets

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
