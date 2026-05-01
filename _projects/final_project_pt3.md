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



<vegachart schema-url="{{ site.baseurl }}/assets/json/Users_0Ddriley_Desktop_0Ddriley32.github.io_07ssets_jsoncompare_murder_rate_lines.json" style="width: 100%"></vegachart>

<img src = '{{ site.baseurl }}/assets/pngs/side_population_grouped_bar.png'>


<vegachart schema-url="{{ site.baseurl }}/assets/json/Users_0Ddriley_Desktop_0Ddriley32.github.io_07ssets_jsonus_murder_rate_line.json" style="width: 100%"></vegachart>



<div class="left">
{% include elements/button.html link="https://github.com/rdriley32/rdriley32.github.io/tree/main/_data" text="Data Spreadsheet Folder" %}
</div>



<div class="right">
{% include elements/button.html link="https://github.com/rdriley32/rdriley32.github.io/blob/main/python_notebooks/Workbook.ipynb" text="Jupyter Notebook" %}
</div>





