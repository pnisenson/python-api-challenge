# python-api-challenge
Included in this repo are the following directories and files:
	A) starter_code - contains starter code Jupyter notebooks provided. This is included for informational purposes only. DO NOT USE IN GRADING.
	B) WeatherPy - contains WeatherPy.ipynb (Jupyter notebook) containing code developed for Part 1. Includes output_data folder with created CSV listing of cities selected and screenshots of all scatter plots. Scatter plots are labeled by attribute being compared to Latitude (e.g. wind.png) and includes hemisphere labeling if applicable (e.g. NHwind.png).
	C) VacationPy - contains VacationPy.ipynb (Jupyter notebook) containing code developed for Part 2. Includes Screenshots folder with 4 shots of the first heatmap (different sections of map, labelled HM1, etc.) and the final heatmap with markers showing hotel info for ideal locations (zoomed in for applicable area of map, labelled MarkerMap).
	D) .gitignore file used to block api_keys.py files from being shared on repo
	E) This README file.


3 Observations from Part 1:
	1) The strongest correlations to latitude were with temperatures. As expected, the closer to the equator a location was, the warmer the temperatures were.
	2) The data reflects a northern hemisphere winter and southern hemisphere summer. Most of the temperatures south of the equator were greater than 60 degrees F, while many north of the equator fell below 60 degrees F. 
	3) None of the other inputs (wind speed, humidity, cloudiness) correlated strongly with latitude. This relects that across lattitudes, locations of geographic features that make these traits inconsistent. For instance, the same latitude may contain a city on a lake, ocean or other water feature that could cause windier conditions or a city in an inland area with no wind. 