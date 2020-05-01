# Data

The different processes involved in this stage are mentioned below

## 1. Collecting Data

* We will use the below wikipedia page to gather the details of all the neighbourhoods in Toronto. 

  https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M

  We will use BeautifulSoup python library for web scraping. 

* Geographical co-ordinates for the neighborhoods are obtained from the below link.
  https://cocl.us/Geospatial_data
  
* Foursquare API will be used to get the list of Indian restaurants in each neighborhood. This can be used to establish a competitor landscape

* We will use 'Statistics Canada' portal to find out the demography details (South Asian population)

https://www12.statcan.gc.ca/census-recensement/2016/dp-pd/prof/details/page.cfm?Lang=E&Geo1=CSD&Code1=3520005&Geo2=PR&Code2=35&Data=Count&SearchType=Begins&SearchPR=01&B1=All

## 2. Data Cleaning

We will bring all the data from step 1 together, into a single dataframe which consists of neighborhoods, postal codes, geo-coordinates and South Asian (or Indian) population details. 

## 3. Data Exploration / Analysis

We will use Foursquare API to explore the Indian restaurants in each neighbourhood and then we will group rows by neighborhood and then take the mean of the frequency of occurrence of Indian restaurants in each neighborhood. A similar exercise is performed for population as well

## 4. Clustering

The final stage would be clustering where in k-Means clustering technique to come up with multiple clusters based on competitor landscape and South Asian population.

This final stage will help AJ hospitality to make an intelligent decision as to where the restaurant should be located. 
