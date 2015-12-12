googleearthplot
===============

Python library for plotting on google earth

## Galleries

![barchartssample.png](https://github.com/AtsushiSakai/googleearthplot/blob/master/img/barchartssample.png)

![barchartsample.png](https://github.com/AtsushiSakai/googleearthplot/blob/master/img/barchartsample.png)

## Requirements

### simplekml

- [Overview SIMPLEKML 1.2.8 documentation](http://www.simplekml.com/en/latest/index.html)

install:

> pip install simplekml

### pandas

- [Python Data Analysis Library $(Q!=(B pandas: Python Data Analysis Library](http://pandas.pydata.org/)

install:

> pip install pandas

## Google Earth (Pro)

- [Google Earth](http://www.google.com/earth/download/ge/agree.html)

install:

from the upper link

## Install

## Usages

This library generates a kml file for plot.

### A bar plot 

You can plot a bar chart with the code

    #A bar plot 
    gep1=googleearthplot()
    lat=18.333868#degree
    lon=-34.038274#degree
    num=100 #bar height size
    size=1  #meter
    name="barsample"
    color="red"
    gep1.PlotBarChart(lat,lon,num,size,name,color);
    gep1.GenerateKMLFile(filepath="sample1.kml")

If you click the generated kml file,

you can see the plot on Google Earth.

![barchartsample.png](https://github.com/AtsushiSakai/googleearthplot/blob/master/img/barchartsample.png)


### Bar plots from csv data


## Licence

[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)

## Author

[AtsushiSakai](http://atsushisakai.github.io/)


