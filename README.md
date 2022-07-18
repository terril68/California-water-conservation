{\rtf1\ansi\ansicpg1252\cocoartf2580
\cocoatextscaling0\cocoaplatform0{\fonttbl}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
} 
# Climate change's impact on water in California
For this class project, I wanted to look at the water conservation efforts in California during droughts. To find out, I downloaded and analyzed the monthly urban water supplier reports on potable water production and consumption from the state's water boards. I compared water production and R-GPCD, which stands for residential gallons per capita per day, from 2014 to 2022. I first looked at the statewide data and then zoomed in on water consumption of each of California's 10 hydrologic regions. I found out that water production is positively correlated with water consumption. In other words, both water production and usage increase during warmer periods. This makes me wonder how effective mandatory restrictions are in curbing water usage.
# My data collection process
I downloaded the 2014-2022 monthly urban water supplier reports on potable water production and consumption from [California's Water Boards](https://www.waterboards.ca.gov/water_issues/programs/conservation_portal/conservation_reporting.html). I then loaded the data into Panda and analyzed it. I also used Altair to visualize the data in Panda, before cleaning it up in Adobe Illustrator.  Finally, I used ai2html to export my graphics as HTML files.
# What my repository contains
## Jupyter notebook
water.ipynb: data analysis on data from [California's Water Boards](https://www.waterboards.ca.gov/water_issues/programs/conservation_portal/conservation_reporting.html)
## Data
uw-supplier-data060722 3.csv: the monthly urban water supplier reports on potable water production and consumption from 2014-2022
statewide_production.csv: statewide water production dataset created in Panda by using the uw-supplier-data060722 3.csv data
statewide_usage.csv:statewide water usage dataset created in Panda by using the uw-supplier-data060722 3.csv data
## Charts
statewide_production: statewide water production from 2014 to 2022
# What I learned
I learned to use Altair to visualize my data in Panda. I also learned to use AI to clean up and add annotations to my data. I also experienced with ai2html and learned the different ways to use it, such as creating responsive data.
# Future improvements
In the future, I would like to use more visualization tools, such as the Bootstrap CSS framework, to make my website more appealing. I didn't include water used for agricultural purposes in my analysis, which is actually a huge component of water usage in California. The state boards' data didn't include this information, so in the interest of time, I decided to not analyze agricultural usage for this project. I would definitely like to include it for a more holistic analysis in the future. 