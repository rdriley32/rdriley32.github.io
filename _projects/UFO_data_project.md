---
name: UFO Data Project
tools: [Python, HTML, vega-lite]
image: assets/pngs/ufo_chart.png
description: This is from homework 5
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# UFO Data Homework 5


<vegachart schema-url="{{ site.baseurl }}/assets/json/ufo_chart.json" style="width: 100%"></vegachart>


The first graph is a line chart that shows the average UFO sighting duration in seconds over time for all US States included in the dataset. I grouped the data by date and state and then the mean of duration of sightings in seconds. Using the mean removes some of the outliers that are present in the data. The x axis shows the time in years and is a temporal scale which is used for data related to time. The y axis is the duration of the sighting in seconds and is a quantitative scale because that data is numerical and we are looking at the size of each value in reference to each other. We are also using a “symlog” due to the large variation of values which makes a better representation of the values in the visualization.  

For interactivity, I included a dropdown menu that allows the user to select a state and have that state’s information show on the graph. My initial idea was to show all state’s graphs and highlight them, bold them, and gray the other lines out to make them less visible. However, this did not work as there were too many states to accommodate and it made it very difficult to be able to see the data clearly. I then did some google searches to see if there was a way to get one line to show up and hide the rest so only one line would be visible. I found this vega- altair explanation, https://altair-viz.github.io/user_guide/transform/filter.html#transform-options,  of filter which mentioned you could transform objects based on the selection.



## Search The Data & Methods

Below is where we can put some links to both the data and the analysis code as buttons:

```
<div class="left">
{% include elements/button.html link="https://github.com/vega/vega/blob/main/docs/data/cars.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://blog.4dcu.be/programming/2021/05/03/Interactive-Visualizations.html" text="The Analysis" %}
</div>
```

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/vega/vega/blob/main/docs/data/cars.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jnaiman/online_cv_public/blob/main/python_notebooks/test_generate_plots.ipynb" text="The Analysis" %}
</div>

