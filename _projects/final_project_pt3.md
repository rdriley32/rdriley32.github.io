---
name: Final Project Part 3 - US Murder Rates by State
tools: [Python, HTML, vega-lite]
image: assets/pngs/Murder Rate by US Statee.png
description: This is my final project pt 3
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Murder Rate by US State (2010-2024)

Ryan Riley

<vegachart schema-url="{{ site.baseurl }}/assets/json/Users_0Ddriley_Desktop_0Ddriley32.github.io_07ssets_jsonus_murder_rate_line.json" style="width: 100%"></vegachart>

This graph shows the average murder rates for each US state from the years 2010 to 2024. Using the dropbox above, you can select which state you would like to view. The state you select will highlight while the other states will be grayed out. This will allow you to compare the other states average murder rate to the state you selected. You will be able to see the trend of murder rates over the time period. Source: U.S. Department of Justice, Federal Bureau of Investigation. (2025). FBI crime statistics [Data set]. DatHere. https://data.dathere.com/dataset/fbi-crime-statistics



# Total Murder Rates for the Australia (2010-2024)
<vegachart schema-url="{{ site.baseurl }}/assets/json/Users_0Ddriley_Desktop_0Ddriley32.github.io_07ssets_jsonaustralia_homicide_bars.json" style="width: 100%"></vegachart>

This chart shows the murder rates for the Australia from the years 2010 to 2024. This data shows that, relative to the US, Australia has a much lower murder rate. To get the data needed for this graph, I had to delete other unneeded tables that were included in the excel spreadhseet and convert it as a csv file. I deleted the title of the spreadsheet in the first row. I added column title "Years" for the column with year values. I deleted all rows before 2010 and change the values of the Year column to a single year. I also removed the row for 2025 and removed the text that sourced the file. I also removed the totals for all rows and columns. I changed the titles of the columsn from abbreviations to the full name of the territories. I added a column for total murder for Australia and added all murders in the territories to that column. I added a column for population and filled it in using https://www.macrotrends.net/global-metrics/countries/aus/australia/population. I then divided the population by the murder rate and multiplyed that by 100,000 to get a murder rate of 100,000 popultation. I created this graph using the source listed below. 
Source: Australian Institute of Criminology. (n.d.). SR58. https://www.aic.gov.au/publications/sr/sr58


# Total Murder Rates for the United Kigntom (2010-2024)
<vegachart schema-url="{{ site.baseurl }}/assets/json/Users_0Ddriley_Desktop_0Ddriley32.github.io_07ssets_jsonengland_homicide_bars.json" style="width: 100%"></vegachart>

This chart shows the murder rates for the United Kingdoom from the years 2010 to 2024. This data shows that, relative to the US, England has a much lower murder rate. To get the data needed for this graph, I had to remove rows with text describing what the spreadsheet is and some additional notes. I simplified the names of the columns (year ending to years, number of homicides to homicides) and changed the values of the years from an erronous date caused by Excel to a single year. I also deleted all years outside of 2010 to 2024. I added the population column and filled it in using https://www.macrotrends.net/global-metrics/countries/gbr/united-kingdom/population. I then divided the population by the murder rate and multiplyed that by 100,000 to get a murder rate of 100,000 popultation. I created the graph using the source below. 
Source: Office for National Statistics. (2026, February 5). Homicide in England and Wales: Year ending March 2025. https://www.ons.gov.uk/peoplepopulationandcommunity/crimeandjustice/articles/homicideinenglandandwales/yearendingmarch2025

<vegachart schema-url="{{ site.baseurl }}/assets/json/Users_0Ddriley_Desktop_0Ddriley32.github.io_07ssets_jsoncompare_murder_rate_lines.json" style="width: 100%"></vegachart>

This is a line graph that shows the comparison of US murder rates, Australian murder rates, and United Kingdom murder rates. As you can see, the US has almost four times the murder rates of the other two countries. This graph was created by me using the sources mentioned above.  

<div class="left">
{% include elements/button.html link="https://github.com/vega/vega/blob/main/docs/data/cars.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/rdriley32/rdriley32.github.io/blob/main/python_notebooks/Workbook.ipynb" text="The Analysis" %}
</div>

edit
