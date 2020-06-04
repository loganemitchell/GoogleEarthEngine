# Google Earth Engine Tools

Recently I started playing around with Google Earth Engine to visualize satellite data sets.  My first foray into this was producing a map that compared Tropomi NO2 during March 15-30 in 2019 vs 2020 to visualize the impact of the Covid-19 lockdown on NO2 concentrations.  I wanted to compare this satellite data to surface observations of air pollutants and GHGs in Salt Lake City.  That writeup can be found here:
https://atmos.utah.edu/air-quality/covid-19_air_quality.php

And the Google Earth Engine App that shows Tropomi NO2 can be found here:
https://loganmitchell.users.earthengine.app/view/covid-19-and-air-quality-in-utah


This is an exceptionally useful tool to visualize satellite data sets.  To help others get started in playing around with this, this repository will host code to produce that visualization and updates to it over time.  There is a lot of potential to use this tool to develop quantitative undergraduate labs/projects analyzing satellite data sets.


- Step 1: Sign up for a Google Earth Engine account https://earthengine.google.com/signup/
- Step 2: Open up the code editor https://code.earthengine.google.com/
- Step 3: Make a new script and Copy/Paste the code into it.
- Step 4: Click the "Run" button above the code editor window.
- Step 5 (optional): To make an "App" with a dedicated URL, click on "Apps" and then "New App"


Here is some more information/documentation:
- Example Earth Engine apps (I followed the code in these apps to make my own): https://www.earthengine.app/
- Earth Engine data sets available: https://developers.google.com/earth-engine/datasets/
- Tutorials: https://developers.google.com/earth-engine/tutorials


There are several things that would be useful to add that I haven't had a chance to do yet:
- Add a legend or color bar
- Add labels to the map.  For example, I thought this was useful & would be neat to embed into the map: https://twitter.com/J_I_Fisher/status/1265327283864244228
- Some way to add up or average the column NO2 in some area (defined with a rectangle, or a KML shape, or something like that).


If you figure out how to any of these, I'd appreciate it if you could share that back to me so this code can be updated.


An idea for an undergrad lab is to download EIA data from a power plant and compare the electricity production to NO2.  For example, here is a map of all Wyoming power plants in the EIA dataset:
https://www.eia.gov/state/index.php?sid=WY


If you browse to a coal plant you can click on "View Data in the Electricity Data Browser" and look at the data.  Here is the Jim Bridger power plant a little NE of Rock Springs WY (compare March 2019 when they produced 1087 GWh to March 2020 when they produced 827 GWh).  Note that there is some annual variability in electricity production, so some of the 2019-2020 difference could be due to reductions in electricity demand from Covid-19, or it could be seasonal maintenance, or a combination of the two, or something completely different
https://www.eia.gov/electricity/data/browser/#/plant/8066


An example of how this tool can be used can be seen in this <a href="https://trib.com/news/state-and-regional/energy-journal-pollutants-from-coal-decline-during-covid-19-in-wyoming/article_c9263410-c132-51d9-8745-4a42ba85b40c.html">article from the Casper Star Tribune</a>.
