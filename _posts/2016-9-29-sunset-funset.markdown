---
layout: post
title:  "Sunset Funset"
date:   2016-9-29 18:22:01
categories: project
---
Sunset Funset uses topographic data from the USGS to find sunset viewing locations. Optimal locations within a user specified area and search radius are determined by finding local maxima, filtering them according to potential sunset visibility, ranking them using a variety of scores, and returning the final points plotted on a Google Map with corresponding pictures from the Flickr API. The project stores data on and is deployed on AWS.

![completion rate by state]({{ site.url }}/images/screenshot.png)

Try your own search  [here](http://www.sunsetfunset.com/)!

See the code for the full project [here](https://github.com/sajafleming/Sunset-Funset). Data for this project is from [the USGS](http://viewer.nationalmap.gov/basic/)