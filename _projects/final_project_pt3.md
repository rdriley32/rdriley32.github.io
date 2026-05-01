---
name: Final Project Part 3 - US Murder Rates by State
tools: [Python, HTML, vega-lite]
image: assets/pngs/grouped_bar_chart.png
description: This is my final project pt 3
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Homicide Trends: A Data Comparison of Homicide Rates Across the US, UK, and Australia (2010-2024)

Ryan Riley

<img src = '{{ site.baseurl }}/assets/pngs/grouped_bar_chart.png'>

The first bar graph shows a comparison of murder rates per 100,000 people in the United States, United Kingdom, and Australia from the years 2010 to 2024. In 2017, the United States had a murder rate per capita of approximately 5.02. This means that for every 100,000 people in the United States, there were about five murders. 
You can see that the United States has the highest murder rate per capita compared to the other two countries. The United States’ murder rate is approximately four to six times higher than the other two countries and is much more dynamic. The content of this graph was created by government agencies from each country who track and collect crime. 
We can note that the years 2020 to 2023 see a large spike. This is most likely due to the Covid pandemic where crime spiked overall. However, we can see that the UK and Australia did not have a significant spike during that time. A bar graph is used for this data to show the sheer number of murders per capita present in all countries. 



<vegachart schema-url="{{ site.baseurl }}/assets/json/Users_0Ddriley_Desktop_0Ddriley32.github.io_07ssets_jsoncompare_murder_rate_lines.json" style="width: 100%"></vegachart>

The second graph is a line chart which shows the same data, but in a different format. The line chart lets us see the overall trends of the murder rate more easily than the bar graph. The gap between the United States’ line and the lines of the United Kingdom and Australia are glaring. 

<img src = '{{ site.baseurl }}/assets/pngs/side_population_grouped_bar.png'>

For reference, this graph shows a comparison of the populations between the United States, the United Kingdom, and Australia. Here we see that the United States has approximately five times the population of the United Kingdom and approximately 13 times the population of Australia. This further shows that the United States has a large murder problem that isn’t seen in the other two countries. 

<vegachart schema-url="{{ site.baseurl }}/assets/json/Users_0Ddriley_Desktop_0Ddriley32.github.io_07ssets_jsonus_murder_rate_line.json" style="width: 100%"></vegachart>

The last graph is a comparison line chart for the murder rates of all US States over the years of 2010 to 2024. At first this graph may look very confusing, but using the dropdown box below the graph, you will be able to select the state you would like to look at. Once you select a state, the color of that state’s line is highlighted, and all other states turn to a light gray. This is to allow you to still compare to the other states. For this graph I chose the color scheme “dark2” as it had less similarities in the choice of colors for each line. However, there are more states than colors in that scheme and some colors repeat. 

<div class="left">
{% include elements/button.html link="https://github.com/rdriley32/rdriley32.github.io/tree/main/_data" text="Data Spreadsheet Folder" %}
</div>



<div class="right">
{% include elements/button.html link="https://github.com/rdriley32/rdriley32.github.io/blob/main/python_notebooks/Workbook.ipynb" text="Jupyter Notebook" %}
</div>


Citations for sources of all graphs are located in the “Date Spreadsheet Folder” in the “Data Spreadsheet Read Me.txt” file. 


