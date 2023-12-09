# 20211130_The Impact of Different Venues on COVID-19 Transmission in the city of Toronto, Canada

- Latest Updated: 20211115
- Readme Edited: 20231209

- Author: Yicong Li
- Link: https://colab.research.google.com/drive/1Ct-O-qq3bDBqi9wT25JBZKja8IQkfWd0?usp=sharing

- Description: This project is an independent project, which explores the influence of different venues categories on the occurrence of COVID-19 cases in the city of Toronto, Canada.

 - Data Description
	- Data about the confirmed and probable cases of patients infected with SARS-CoV-2 virus is provided by Open Data Portal of the city of Toronto. The dataset is refreshed weekly and contains all cases since the beginning of pandemic, January 2020. One of the most important features of this dataset is that is the cases are assigned with geographical information, which is the neighborhoods name.
		- Data Link: https://open.toronto.ca/dataset/covid-19-cases-in-toronto/
 
	- Neighborhood Data of Toronto city is also provided by Open Data Portal. It includes the boundary information of Toronto’s 140 geographically distinct neighborhoods. These data will give us basic geospatial reference for both graph plots and association analysis.
		- Data Link: https://open.toronto.ca/dataset/neighbourhoods/


- API Desciption
	- Foursquare Place API offers access to its global database which contains location-based data of venues, including venue trending, venue categories, venue latitude and longitudes and so on.
		- API Link: https://developer.foursquare.com/docs/places-api/