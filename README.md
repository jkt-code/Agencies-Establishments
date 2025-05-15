# Agencies-Establishments
## How I get data for analysing Rental or property management agencies all over Kenya
Here I have used python to do webscraping using Beautiful soup &amp; web extraction using googlemaps API
This is the link to view the Jupyter Notebook https://anaconda.cloud/share/notebooks/5609d302-2d66-43d7-ba08-45d62662669d/overview
## Kenyan Towns Extraction
I used python's package Beautiful soup to scrape the site https://geokeo.com/database/town/ke/ to get the data from the tables in that site.

## Google Maps Data Extraction
I used python requests package to use google maps' api to extract data from google maps using the parameters: type, location, radius etc.
 #### radius
 This parameter specifies the radius of search ie 30000 represents 30000 meters which is 30km.
 #### type
 Using https://developers.google.com/maps/documentation/places/web-service/legacy/supported_types you can find the types of businesses, places etc using this type manual that  extraction of data. In our case I used "rental_estate_agency" and "establishment". I used the data of towns i had extracted to loop over each town to get results of the 
 businesses with that type and within that radius, rasius of search, in this case it was 30 km radius.
