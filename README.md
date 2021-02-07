### python-api-challenge

In this homework assignment, we were to review weather data on two fronts: 1) data across cities based on varying distance from the equator and 2) plan future vacations based on this weather data.  To date (1/7/2021), this submitted homework only addresses the first portion.

## What you'll find in this workbook
1. A series of scatter plots showing the relationhip across cities between latitude and four other metrics: max temperature, humidity, cloudiness, and wind speed.  Heading each plot is a short comclusion summary.
2. A series of linear regression plots on each of the above but separared into northern and southern hemispheres.  (Note that northern = latitude of 0 and greater.  Southern = latitude of less than 0.)  After each of these 8 plots is a short conclusion summary.

In order to run this notebook yourself, you'll need your very own API key. Replace the "YourAPIKeyHere" in the config file with your own key.  To share my key is to share my credit card which is to by pizzas for all of the graders.  I don't know who you are and I'll buy you a pizza at the end of the course if I pass.

## Conclusions
As expected, max temperature for cities appears to be tied to latitude, but not equally across northern and southern hemispheres. The southern hemisphere tends to have higher humidity in general.  The northern hemisphere tends to have decreasing max temperatures the further away from the equator.  There were not strong correlations latitudes vs humidity, cloudiness, and wind speed based on the latitude of the city, which is not surprising.


## Below are the requirements of the homework from the class syllabus for any additional reference.

# Python API Homework - What's the Weather Like?

## Background

Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. So let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

Now, we know what you may be thinking: _"Duh. It gets hotter..."_

But, if pressed, how would you **prove** it?

![Equator](Images/equatorsign.png)

### Before You Begin

1. Create a new repository for this project called `python-api-challenge`. **Do not add this homework to an existing repository**.

2. Clone the new repository to your computer.

3. Inside your local git repository, create a directory for both of the Python Challenges. Use folder names corresponding to the challenges: **WeatherPy**, **VacationPy**.

4. Inside the folder you just created, add new files called `WeatherPy.ipynb` and `VacationPy.ipynb`. These will be the main scripts to run for each analysis.

5. Push the above changes to GitHub.