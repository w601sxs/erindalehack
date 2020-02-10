# Erindale hack

## Use data provided by Erindale SS to point students to the spots with the best Wifi and least noise!

Please click the ipynb file for more details on the algorithm

![Heatmap of composite score](heatmap.PNG)

## Inspiration
It's always difficult to find the place with the least noise and best WiFi to get work done, and that could be class work or last minute homework! 

## What it does
This app will help students head to this location with live data. As long as you use the latest .json file dump provided, you can get real time updates of where to head towards. The algorithm used to come up with appropriate composite score for finding points with maximum wifi and minimum noise levels.

## How I built it
I used folium, a package in python and jupyter notebooks. Jupyter notebook is an interactive tool, that can be used to explore data. The advantage of using this is that students who want to extend this work can use this is as a starting point. 

## Challenges I ran into
Lack of data - with more data, we could have thought of using more complicated Machine learning algorithms to provide better insight. But the advantage here is that this is a good starting point for ingesting historical data. 

## Accomplishments that I'm proud of
Since this is written in python, it can also be easily converted to a Flask web app, that shows this interactive visulalization online. To do this using DigitalOcean, follow this tutorial https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-uswgi-and-nginx-on-ubuntu-18-04


![DigitalOcean with Flask](https://content.nanobox.io/content/images/2017/09/flask-digitalocean-banner.png)

## What I learned
This data can be used to create time-series representation of changes in temperature, humidity, noise and wifi although we did not use the time column here. With more data, we could also find the relationship between these variables, and come up with a better composite score.  

## What's next for "Interactive data Visualization for best place to work"
Converting to something that is hosted in the cloud

## Built With
Python, Jupyter
