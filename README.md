# Access to Parks and Fitness Facilities in Manhattan

Access to green space has been shown to improve both [physical](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3444752/) and [mental](https://www.pnas.org/content/116/11/5188) health. More than [80% of adults in the US](https://www.hhs.gov/fitness/resource-center/facts-and-statistics/index.html) don't meet the recommended guidelines for physical activity. Although green space and exercise are vital to our health, many Americans live in neighborhoods that lack access to these spaces.

This project aims to explore this issue by characterizing Manhattan neighborhoods based on access to parks and sports/fitness facilities. The level of access to these facilities across different neighborhoods is then explored in relation to socio-economic factors such as income.

## Requirements
This project uses the following Python libraries:
* `numpy` : For handling data in a vectorized manner.
* `pandas` : For analyzing datasets.
* `json` : For handling JSON files.
* `requests` : For handling requests.
* `geopy` : For converting an address into latitude and longitude values.
* `folium` : For rendering maps.
* `Matplotlib` : For creating graphs and plots.
* `sklearn` : For performing k-means clustering.
* `yellowbrick` : For finding the elbow point for k-means clustering.
* `shapely` : For calculating centroids of polygons.

## Getting Manhattan Neighborhood Data
Before park and fitness access can be analyzed by neighborhood, we must define the neighborhoods, along with geographical coordinates representing them. In order to explore the relation These tasks are completed in the notebook titled [Manhattan-neighborhood-data.ipynb](https://github.com/racinenassau/mahattan-park-and-fitness-access/blob/master/Manhattan-neighborhood-data.ipynb). The resulting data can be found in [manhattan-neighborhood-data.csv](https://github.com/racinenassau/mahattan-park-and-fitness-access/blob/master/manhattan-neighborhood-data.csv).

## Analyzing Park and Fitness Facility Access
Data on parks, gyms, fitness classes, and sports facilities in each Manhattan neighborhood is collected using the [Foursquare API](https://developer.foursquare.com/). Using this data, the neighborhoods are grouped into clusters based on their access to these facilities. The relation of these clusters to socio-economic data such as income is then explored to investigate how poverty and wealth affect access to some of the key public areas and private services that affect our health. These tasks are completed in the notebook titled [Manhattan-fitness-facility-access.ipynb](https://github.com/racinenassau/mahattan-park-and-fitness-access/blob/master/Manhattan-fitness-facility-access.ipynb)
