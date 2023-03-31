# leaflet-challenge
![Alt text](https://github.com/DunieCarrasco/leaflet-challenge/blob/main/Starter_Code%202/Images/1-Logo.png?raw%3Dtrue)

# Background
The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

# Instructions
The instructions for this activity are broken into two parts:

* Part 1: Create the Earthquake Visualization

<img width="1440" alt="Screenshot 2023-03-30 at 5 18 43 PM" src="https://user-images.githubusercontent.com/117786548/228992576-225bd22b-6484-4043-b371-861de4272a77.png">

Your first task is to visualize an earthquake dataset. Complete the following steps:

1. Get your dataset. To do so, follow these steps:

* The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON FeedLinks to an external site. page and choose a dataset to visualize. The following image is an example screenshot of what appears when you visit this link:

![3-Data](https://user-images.githubusercontent.com/117786548/228992917-86d04740-a7c9-4fce-ab02-53aacfee6cca.png)

When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization. The following image is a sampling of earthquake data in JSON format:

![4-JSON](https://user-images.githubusercontent.com/117786548/228992965-6d298401-88cd-4a10-b751-cd7351cefe96.png)

2. Import and visualize the data by doing the following:

* Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.

  * Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.

  * Hint: The depth of the earth can be found as the third coordinate for each earthquake.

* Include popups that provide additional information about the earthquake when its associated marker is clicked.

* Create a legend that will provide context for your map data.

* Your visualization should look something like the preceding map.

<img width="1440" alt="Screenshot 2023-03-30 at 5 18 59 PM" src="https://user-images.githubusercontent.com/117786548/228993423-0b7b0626-7b7a-4388-a766-beaf6660a68d.png">

# Requirements
These requirements apply only to "Part 1: Create the Earthquake Visualization" as "Part 2" is optional with no extra points earning.

# Map (60 points)
TileLayer loads without error (20 points)

* Connects to geojson API using D3 without error (20 points)

* Markers with size corresponding to earthquake magnitude (10 points)

* A legend showing the depth and their corresponding color (10 points)

# Data Points (40 points)
* Data points scale with magnitude level (10 points)

* Data points colors change with depth level (10 points)

* Each point has a tooltip with the Magnitude, the location and depth (10 points)

* All data points load in the correct locations (10 points)

# References
Dataset created by the United States Geological SurveyLinks to an external site..
