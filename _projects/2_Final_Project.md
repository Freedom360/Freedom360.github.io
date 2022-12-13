---
name: Billionaire Status, Wealth Size, and Location from 1996-2014
tools: [Python, HTML, vega-lite]
image: assets/pngs/gender_chart.png
description: IS 445 Final Project
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Billionaire Status, Wealth Size, and Location from 1996-2014

## Team
- Donlapun (Dorothy) Wongkarnta (netid: dw16)
- Riya Shah (netid: rshah257)
- Ethan Wee (netid: edwee2)

## Dataset
In this project we will explore the Billionaire Dataset to find the meaning insights such as the association of different factors that might influence the wealth worth of the billionaires and shows in the visualizations as the findings with the writeup. The information about the dataset can be founded [here.](https://corgis-edu.github.io/corgis/csv/billionaires/)

#### Data Citation
Ryan Whitcomb. CORGIS Datasets Project. https://corgis-edu.github.io/corgis/csv/billionaires/. Accessed 1 Dec. 2022.


## Visualizations


#### Interactive Visualization between the Line Graph of the Wealth Worth in Billions by Year Company Founded and the count of the Year Company Founded
<vegachart schema-url="{{ site.baseurl }}/assets/json/wealth_worth_year_founded.json" style="width: 100%"></vegachart>

The graph on the left is the line graph between the year company is founded in and the wealth worth in billions. The user can select the interval of the graph in order to see the histogram that shows the count of the year (in interval). We can see that there is an positive association between the year company is founded and the wealth worth in billions after 1500. The histogram shows the distribution of those years in more depth as it counts the how many companies are in each year. This helps us understand that even though there is an association between the year company is founded and the wealth worth in billions after 1500, the number of new companies that founded in each year does not have influence on the wealth worth in billions.


#### Interactive Visualization between the  Scatter Plot between the Demographics Age and Wealth Worth in Billions of the Billionaires and Histogram of the Location Region of the Billionaire Company
<vegachart schema-url="{{ site.baseurl }}/assets/json/wealth_worth_age.json" style="width: 100%"></vegachart>

This interactive visualization shows the relationship between a billionaire’s demographic age and wealth worth and the region they are from. The user can select an age on the demographics age chart and the region bar graph will update accordingly, showing the number of billionaires at that age for each region. From this visualization, we can interpret that most billionaires are 50 years old or above. We can also interpret that as the age increases, a lot of billionaires are from North America, but there are also a good number of billionaires from Europe and South Asia. There is not a clear association between a billionaire’s age, wealth worth, and the region they are from, but it helps in providing context about the overall age of billionaires in different regions.

### Contextual Visulizations

#### Histogram of Billionaire by Gender
![Billionaires by Gender](https://raw.githubusercontent.com/Freedom360/Freedom360.github.io/master/assets/pngs/gender_chart.png)

This contextual visualization shows the distribution of the billionaire gender in the dataset. We can see that the majority of the billionaires are male which is around more than 4 times of the number of female billionaires. The number of the married couple as billionaires is very small. Therefore, the gender of the billionaires might actually influence the wealth worth of the billionaires.

#### Bar Chart of Billionaire’s Wealth Around the World in 2021, by Asset Allocation
 ![Billionaire Wealth by Asset](https://user-images.githubusercontent.com/73120382/205422632-bf097b81-144a-4da4-b5e2-c8986e730676.png)

This image shows a breakdown of Billionaires’ wealth from across the world by the type of wealth they have. In this, we see that with technology billionaires, by far the largest amount of their assets is in public holdings, compared to real estate billionaires who’s largest asset type is actually private holdings. Interestingly, fully half of the share of wealth within industrial conglomerate billionaires are formed by public holdings. What this could suggest is that technology industry billionaires main source of wealth comes from their stock allocation, such as their salaries being paid for in shares of the public company they control. This makes sense as many tech CEO’s such as Elon Musk are often paid a base salary, with stock options used as incentives. This would result in CEO’s with high performing companies being compensated with valuable stock options.

[External Link](https://www.statista.com/statistics/299134/billionaires-breakdown-wealth/)

#### Scatter Plot of GDP per Capita by Country in 2022
 ![GDP per Capita by Country 2022](https://github.com/Freedom360/Freedom360.github.io/blob/master/assets/pngs/gdpGraph.png?raw=true)

This visualization provides further context to the billionaires dataset. From this chart we can see the total GDP per capita for each country during 2022. This can be used to compare the 2016 GDP in the dataset and further understand the relationship between a billionaire’s country and the GDP. It can help determine if a billionaire’s country of origin and GDP plays a factor in their status or net worth. An interesting point about this visualization is that the top three countries with the highest GDP are Singapore, Luxembourg, and Ireland instead of United States, considering a lot of billionaires are from the United States. This suggests that a country’s GDP might not be a factor in achieving billionaire status and provides a new perspective when conducting analysis.

[External Link](https://worldpopulationreview.com/country-rankings/gdp-per-capita-by-country)


## Additional Information

### Citations

#### Interactive Visualizations
Used code from class
- [Week 9](https://starboard.gg/jnaiman/inClass_week09_online_fall2022-noY2U59)
- [Week 10](https://starboard.gg/jnaiman/inClass_week10_online_fall2022-nrSZM7g)

### Contextual Visualizations

#### Histogram
Made by the team using Python<br>
[Code](https://starboard.gg/nb/nxupkrI)

#### Bar Chart
Published by Statista Research Department, & 22, S. (2022, September 22). Billionaires: Breakdown of wealth by asset 2021. Statista. Retrieved December 2, 2022, from <https://www.statista.com/statistics/299134/billionaires-breakdown-wealth/>

#### Scatter Plot
World Population Review. *GDP per Capita by Country 2022*. <https://worldpopulationreview.com/country-rankings/gdp-per-capita-by-country>.Accessed 2 Dec. 2022.

<!-- these are written in a combo of html and liquid 

<div class="left">
{% include elements/button.html link="https://github.com/vega/vega/blob/main/docs/data/cars.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jnaiman/online_cv_public/blob/main/python_notebooks/test_generate_plots.ipynb" text="The Analysis" %}
</div> -->

