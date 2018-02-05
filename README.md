# GEOG483 Final Project
This project provides a friendly interface to the City of Waterloo's Open Data Portal by implementing NLP, web mapping, and a friendly bot. 

## Starting the web server
To initialize the web server, you must have Python downloaded and in your [system environment PATH variable](https://superuser.com/questions/143119/how-do-i-add-python-to-the-windows-path).

Once that is setup, simply double click the startserver.py to run it, and then navigate to [www.localhost:8000](http://www.localhost:8000/) in your favourite web browser.

## Index.html
At the time of the initial commit, the index.html file is just a simple leaflet map without any bells and whistles that display MapBox tiles. It prompts the user for input, of which the only acceptable answers are _buildings_ and _parks_, which will then show the desired layer, drawing directly from the City's hosted later on ArcGIS online.
