---
name: Vega Lite Example Project
tools: [Python, HTML, vega-lite]
image: assets/pngs/cars.png
description: This is a "showcase" project that uses vega-lite for interactive viz!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Homework - 10, Group - 11
## Team Members: 
#### Akshya Yadav
#### Deepanshu Malhotra
#### Shruti Jain

# Visualization 1  
<vegachart schema-url="{{ site.baseurl }}/assets/json/Viz1.json" style="width: 100%"></vegachart>

# Visualization 2
<vegachart schema-url="{{ site.baseurl }}/assets/json/Viz2.json" style="width: 100%"></vegachart>


## Search The Data & Methods


<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_bcubcg_fall2022/main/data/building_inventory.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/akshyay2/HW-10/blob/main/Group11_Homework_10.ipynb" text="The Analysis" %}
</div>

