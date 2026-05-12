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


# The United States Has a Murder Problem: A Data Comparison of Homicide Rates Across the US, UK, and Australia (2010-2024)

Ryan Riley

The United States has a serious murder problem. In the developed world, the United State has the highest rates of homicides by a wide margin. There are many possible causes that could contribute to this fact like population or the United States’ violent history. Others believe that the most contributing factor is that guns are readily accessible in the United States while other developed countries have stricter gun laws. 

The line chart below represents the murder rate per capita for each US State from 2010 to 2024. Using the dropdown below the graph, you can select which state you would like to highlight. That state’s murder rate line will be highlighted with its corresponding color while all the other lines turn to gray. This allows you to effectively compare where each state’s murder rate is to other states. As you can see, Louisiana has the highest murder rate per capita in the United States with a high of 16 murders per 100,00 people in 2022. Already the presumption that an area with a high population will have more murder is challenged. Louisiana is roughly the 25th largest state by population in the United States yet is has the highest murder rate in the nation. The state with the highest population, California, has not gone above the rate of 6 murders per 100,000 people in the same time frame. The second largest state, New York, has even less murders than California. 


<vegachart schema-url="{{ site.baseurl }}/assets/json/Users_0Ddriley_Desktop_0Ddriley32.github.io_07ssets_jsonus_murder_rate_line.json" style="width: 100%"></vegachart>



Let’s include data from other developed countries to see where the United States compares to them. Murder rates from the United Kingdom and Australia were used for this comparison. The graph below is a grouped bar chart that shows the murder rates of the United States, The United Kingdom, and Australia. Immediately, you can see that the murder rates for the United States are approximately six times higher at it’s peak that that of the UK and Australia. At the same time, the murder rates of the United Kingdom and Australia are comparable and are far less dynamic than the United States. The murder rate in the US jumps significantly during the years of the Covid Pandemic yet the other two countries did not experience that same spike. 



<img src = '{{ site.baseurl }}/assets/pngs/grouped_bar_chart.png'>


Below is line chart that shows the overall murder rates of each country. The staggering difference is made even clearer here. 


<vegachart schema-url="{{ site.baseurl }}/assets/json/Users_0Ddriley_Desktop_0Ddriley32.github.io_07ssets_jsoncompare_murder_rate_lines.json" style="width: 100%"></vegachart>



Below is another grouped bar chart that shows the population of all three countries. We can see that the United States’ population is approximately five times more than that UK and 13 times more than Australia. The significant difference in populations is not a significant factor in the discussion of why America has a murder problem. 


<img src = '{{ site.baseurl }}/assets/pngs/side_population_grouped_bar.png'>


So why does the United States have a murder problem? Some like to point the America’s violent past of the Revolutionary War, the Wild West, and the harsh trails of frontier life and Manifest Destiny as a possible cause. We have had a bloody history that we can’t shake. Yet, the United Kingdom has seen centuries of war and conquest. Because they have been around for such a long time, their history is much bloodier than ours. Australia was founded as a prison colony and was filled with the worst of the worst once upon a time. Yet both those countries have a significantly smaller murder rate comparative to ours. 

However, some point to gun laws as one of the largest contributing factors of his murder problem. The United Kingdom and Australia have some of the strictest gun laws in the developed world. In both countries, civilians are only allowed to own certain types of firearms. More importantly, there are strict laws on how and where those firearms are stored. In both the UK and Australia, you must obtain a license to own a firearm and show that you have a need to have one. Self-defense is not a valid reason to own a gun in either of those countries. They also mandate that all firearms must be stored in sealed, locked containers. The United States has none of the regulations. It is most likely that the United States’ murder problem is a directly linked to the access of firearms. 



BREAK



<vegachart schema-url="{{ site.baseurl }}/assets/json/Users_0Ddriley_Desktop_0Ddriley32.github.io_07ssets_jsoncompare_murder_rate_lines.json" style="width: 100%"></vegachart>



<img src = '{{ site.baseurl }}/assets/pngs/side_population_grouped_bar.png'>



<vegachart schema-url="{{ site.baseurl }}/assets/json/Users_0Ddriley_Desktop_0Ddriley32.github.io_07ssets_jsonus_murder_rate_line.json" style="width: 100%"></vegachart>

BREAK 

<div class="left">
{% include elements/button.html link="https://github.com/rdriley32/rdriley32.github.io/tree/main/_data" text="Data Spreadsheet Folder" %}
</div>



<div class="right">
{% include elements/button.html link="https://github.com/rdriley32/rdriley32.github.io/blob/main/python_notebooks/Workbook.ipynb" text="Jupyter Notebook" %}
</div>


Please note that there was no data for the year 2016 in the dataset for the United States Homicide Rates. Citations for sources of all graphs are located in the “Date Spreadsheet Folder” in the “Data Spreadsheet Read Me.txt” file.





