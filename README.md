# topics_in_Digital_Humanities_project


## Working Process
### Our goal was to simplify the way of finding an archive file and improve the user experience.
First we took the raw data and extract the 'location' field which is a name that describes a place.
We used 'geopy' library for Python to get lat/long coordinates from the 'location' field.
In addition we convert the raw data to GEOJSON format which supprted in Kepler open source map.
After that we uploaded the data to Kepler map and now you can use it easily and filter the data you interested in. 

## Technologies

- PYTHON
- GEOJSON
- KEPLER

## How to use it
1. open https://kepler.gl/
2. click 'add layer' button at upper left side of the screen
3. drag 'data.geojson' and load it
4. All set - we’re ready to go :)
(If you faced any problems, just take a look on the video below)


![Example](video.gif)
<br/>


