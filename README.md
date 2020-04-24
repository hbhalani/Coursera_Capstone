# Coursera_Capstone
### Peer-graded Assignment: Capstone Project - The Battle of Neighborhoods


###### Now that you have been equipped with the skills and the tools to use location data to explore a geographical location, over the course of two weeks, you will have the opportunity to be as creative as you want and come up with an idea to leverage the Foursquare location data to explore or compare neighborhoods or cities of your choice or to come up with a problem that you can use the Foursquare location data to solve.

# 1) Introduction/Business Problem
###### Clearly define a problem or an idea of your choice, where you would need to leverage the Foursquare location data to solve or execute. Remember that data science problems always target an audience and are meant to help a group of stakeholders solve a problem, so make sure that you explicitly describe your audience and why they would care about your problem.

*__While opening a restaurant can be a very lucrative business, a lack of demand causes many restaurants to close within the first year of opening. There are many different factors that can account for a restaurant’s success such as location, competition and quality of the food. This is an important question that every business owner must face when choosing whether to open a restaurant or not, as well as location of the business.__*

*__To demonstrate the process of picking a location for a client opening a business, the project will focus on answering the following question: “If the client wanted to open an Indian Restaurant in Toronto, what areas are the best options to open the restaurant?” For an Indian Restaurant, the location and competition are both determined by where the restaurant is opened. If there are too many Indian Restaurants in the local vicinity, the profitability of the restaurant will be severely decreased. Additionally, starting a restaurant in a location with higher income would increase the profitability of the business over starting in a poorer area.__*

# 2) Downloading and Prepping Data

###### Describe the data that you will be using to solve the problem or execute your idea. Remember that you will need to use the Foursquare location data to solve the problem or execute your idea. You can absolutely use other datasets in combination with the Foursquare location data. So make sure that you provide adequate explanation and discussion, with examples, of the data that you will be using, even if it is only Foursquare location data.

*__To provide the stakeholders the necessary information I'll be combining Toronto's 2016 Census that contains Population, Average income per Neighborhood with Toronto's Neighborhoods shapefile and Foursquare API to collect competitors on the same neighborhoods.__*

#### To answer the business problem, the following factors have to be extracted from various data sources:
<ul>
  <li>Population & Ethnic Distribution of Each Neighborhood (Toronto Census)</li>
  <li>Income Distribution of Each Neighborhood (Toronto Census)</li>
  <li>Number of Restaurants in Each Neighborhood (Foursquare API)</li>
  <li>Number of Indian Restaurants in Each Neighborhood (Foursquare API)</li>
</ul>

*__Toronto's Census data is publicly available at this website: https://www.toronto.ca/city-government/data-research-maps/open-data/open-data-catalogue/#8c732154-5012-9afe-d0cd-ba3ffc813d5a__*

*__Toronto Neighborhoods' shapefile is publicly available at this website: https://www.toronto.ca/city-government/data-research-maps/open-data/open-data-catalogue/#a45bd45a-ede8-730e-1abc-93105b2c439f__*
