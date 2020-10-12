# vega-lite-examples
This repository contains vega-lite examples for FIT3179.

## Simple stacked bar chart 
A simple demo of a normalised stacked bar chart. 

Preview: https://kadeksatriadi.github.io/vega-lite-examples/examples/normalised-stacked-bars.html

HTML: https://github.com/KadekSatriadi/vega-lite-examples/blob/main/examples/normalised-stacked-bars.html

Vega-lite JSON: https://github.com/KadekSatriadi/vega-lite-examples/blob/main/examples/normalised-stacked-bars.json

## Multiple Visualisations
A simple demo of multiple vega-lite visualisations on a single web-page (without styling).

Preview: https://kadeksatriadi.github.io/vega-lite-examples/examples/multiple_visualisations.html

HTML: https://github.com/KadekSatriadi/vega-lite-examples/blob/main/examples/multiple_visualisations.html

Vega-lite JSON (stacked bar chart): see first example.

Vega-lite JSON (line chart): https://github.com/KadekSatriadi/vega-lite-examples/blob/main/examples/line-chart.json

## Stylised Page
The extended version of the multiple visualisations demo with following improvements:
- page layout using Pure.css,
- typography using Google Font,
- responsive vega-lite charts size using <code>"width": "container"</code> property on vega-lite JSON,
- charts' action buttons are hidden with <code>{"actions": false}</code> parameter on <code>vegaEmbed</code> function. 

Preview: https://kadeksatriadi.github.io/vega-lite-examples/examples/using_pure_css.html

HTML: https://github.com/KadekSatriadi/vega-lite-examples/blob/main/examples/using_pure_css.html

Vega-lite JSON (responsive stacked bar chart): https://github.com/KadekSatriadi/vega-lite-examples/blob/main/examples/normalised-stacked-bars-responsive.json

Vega-lite JSON (responsive line chart): https://github.com/KadekSatriadi/vega-lite-examples/blob/main/examples/line-chart-responsive.json

**Note: This is a demonstration on how you can stylise page and is not an example of perfect visualisation page.**

## Dataset > 25 MB
You should avoid using large dataset since Vega-lite is not highly scalable. Due to github limitation, you can't upload a file that is > 25 MB. This makes sense because github is a version control tool and tracking changes of a single large file is not practical. 

The workaround for the data visualisation project is by hosting your dataset on external server. In this example, I use Dropbox to host the Victoria Car Crash csv file (41 MB). You can choose any file hosting but you need to make sure it support **direct link file sharing**. Google Drive, for instance, (to the best of my knowledge, let me know if this is wrong) is out of the list because it does not support direct link. Note that when you share a file on dropbox, the default link will start with https://www.dropbox.com domain. You need to replace this with https://dl.dropbox.com/ to make it a direct link to your file.  

Example: 

[Not direct link] https://www.dropbox.com/s/4qybg0qxhak1ldy/Crashes_Last_Five_Years.csv

[Direct link] https://dl.dropbox.com/s/4qybg0qxhak1ldy/Crashes_Last_Five_Years.csv

<br />

Vega-lite JSON: https://github.com/KadekSatriadi/vega-lite-examples/blob/main/examples/sample_external_link_point_map.json

Vega-lite Editor: [link](https://vega.github.io/editor/#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JACyUAVhDYA7EABoQAdxoATemgCsABh1L4NMljQBmPUrVJMKVKAYAnQWgzY8hAmsGU1DtjiY2AA9KKDYETgIxAEcATyYyHWigmCQAawBGQTVYggBhByQIeAgAfQAZIsxSgDEaUlKATTgkBwhQiGJFEAAzNgdkTDRQTFicOBcoTpAAXxmlZAc04ZBR8cmaByhBCaUemkFBAHkcJCg6WLQdSi0lCBoALwnUDJ15kDhZMLUaWTIVnpnOBDOy9GhwbIuACCeTyAEkACIAUQAcgAVUoIqFopHdNbPED9H6yJDOJRhQQMBCyCBoABMSkwNAQcAAqrI6C5Yi0HLMlII5LRMAw1M9QPsIWoXOUjiiAOJwtGs5F4sYE6IMJCyJk2JmkPkgQTWOgisVgyXS7GK5W4xlqlwarU643694U-oA8GQ9DIuWlVkAJQAQlCUaUUVCALK21b29CycK-UndHZkT5S0H9cHalw7HpDOZzIA)

**Note: It takes a while to load!**

## Maps Examples from Homework Week 9

Github repository: https://github.com/KaneSec/vega_lite


