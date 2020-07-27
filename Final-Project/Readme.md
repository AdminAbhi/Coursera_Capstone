### Coursera Capstone Project: Applied Data Science
# Opening a new Shopping Mall in Delhi, India
Business Problem and recommendation of a good place.

## Introduction
The importance of shopping malls as retailing formats has become increasingly remarkable, and today malls play a significant role in consumers’ lifestyles. But nowadays shopping malls have become not just a place to shop it has become a place where social factors get deeper. Shopping malls are like a one-stop destination for not only various types of shoppers but also for dining at restaurants, watch movies, celebrate, etc. This gives retailers a central location and large crowd at the shopping mall which in turn provides a great distribution channel to market their products and services. Real Estate, builders are also taking interest to build shopping malls to cater to the demand. This also becomes a consistent rental income for the owners. As a result, there are many shopping malls in Delhi and more and more malls are being built. But to open shopping and such that the shopping mall succeeds a lot of factors come into play. Among them, one of the major factors is the location of the shopping mall.

## Business Problem
Since shopping malls are the main interest to various groups therefore they are built and real estate investors invest in these projects. But for shopping malls to attract large crowd there are a few major factors, one of those is location. The objective of this capstone project is to analyze and select the best locations in Delhi, India to open a new shopping mall with high chances of success using data science methodology and machine learning techniques. We will make this decision in this project. This will especially benefit the real estate builders since the Indian retail sector has metamorphosed significantly over the last few decades. Rapid urbanization and digitization, rising disposable incomes, and lifestyle changes of particularly the middle-class has led to a major revolution in the retail sector, projected to grow from the US $672 billion in 2017 to the US $1.3 trillion in 2020. Evolving rapidly from usual ‘Kirana shops’ to large multi-format stores offering a global experience to the e-commerce model that is highly technology-driven, the Indian retail sector has evolved.

## Data
To solve the problem, we will need the following data:

- List of neighborhoods in Delhi. This defines the scope of this project which is confined to Delhi, the capital of India.
- Latitude and Longitude coordinates of the neighborhoods. This required to plot the map and get the venue data
- Venue data, particularly data related to shopping malls. We will use this data to perform clustering on the neighborhoods.

## Data Sources:
- The data of the neighborhoods in Delhi can be extracted from the Wikipedia page. (https://en.wikipedia.org/wiki/Neighbourhoods_of_Delhi)
- Then the latitude and longitude data can be retrieved from the Python geocoder package.
- Then using latitude and longitude data venues can be fetched from Foursquare API.

## Methodology
- Web Scraping Wikipedia page for neighbourhood list.
- Get latitude and longitude using Geocoder.
- Use Foursquare API to get venue data.
- Group data based on the frequency of occurrence of each venue.
- Filter the data for Shopping Malls.
- Perform Clustering.
- Visualize the clusters in a map using Folium.

### For more detailed documentation:
Open link -> : https://github.com/AdminAbhi/Coursera_Capstone/blob/master/Final-Project/Coursera-Capstone-Project-Part-2.pdf

### For link to the Jupyter Notebook:
Click here -> : https://github.com/AdminAbhi/Coursera_Capstone/blob/master/Final-Project/Final_Project.ipynb

## Thank you, hope you like it :)
