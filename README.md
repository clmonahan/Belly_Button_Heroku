# Dynamic Belly Button Biodiversity Dashbaord

## Goal
Create a dynamic, interactive dashboard to explore the Belly Button Biodiversity dataset.

## Data Sources
* Belly Button Biodiversity Project: http://robdunnlab.com/projects/belly-button-biodiversity/

## Method
This project used JavaScript, Plotly, SQLite, HTML, CSS & Bootstrap, Flask, and Heroku app deployment.
* JS code: https://github.com/clmonahan/dynamic-biodiversity-dashboard/tree/master/Belly_Button_Biodiversity/static/js
* HTML code: https://github.com/clmonahan/dynamic-biodiversity-dashboard/blob/master/Belly_Button_Biodiversity/templates/index.html
* SQLite files: https://github.com/clmonahan/dynamic-biodiversity-dashboard/tree/master/Belly_Button_Biodiversity/db
* Flask.py file: https://github.com/clmonahan/dynamic-biodiversity-dashboard/blob/master/Belly_Button_Biodiversity/app.py

## Procedures
1. Create a pie chart that uses data from samples route (/samples/<sample>) to display the top 10 samples.
2. Create a bubble chart that uses data from your samples route (/samples/<sample>) to display each sample.
3. Display the sample metadata from the route /metadata/<sample>
4. Adapt the gauge chart from https://plot.ly/javascript/gauge-charts/ to plot the Weekly Washing Frequency obtained from the route /wfreq/<sample>
5. Update all of the plots any time that a new sample is selected.
6. Deploy Flask app to Heroku.

## Final State
The graph should be interactive so that when the user selects a new sample from the dropdown menu, all of the charts update automatically. 

## Challenges
* Creating the guage chart was a new challenge for me that resulted in a lot of trial and error before getting it to work correctly.
* Deploying the app to Heroku was more difficult than expected.

## Conclusions
Belly buttons have a very diverse biocultures, and there seems to be few similarities between one belly button and the next.
