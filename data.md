# Data Sources

In order to identify an optimal location for InfoDyne's manufacturing business, several factors must be considered.

1. Crime rate by neighborhood:  Infodyne wants to take advantage of the tax and loan incentives, but does not want crime to be a detrimment to its business. Since InfoDyme Management is unfamiliar with the city, an analysis of crime rates and neiborhoods is warranted.

2. Transport location: Infodyne needs quick access to both the interstate highway system and local ports so that it can ship its product at reasonable cost across the world.

3. Local amenities: Once an optimal low crime location has been identified in Baltimore, InfoDyne Management would like to identify locations of interest for its employees such as food, gas, and other local businesses such as schools.

## Crime data
Baltimore City provides a large amount of city data at its https://data.baltimorecity.gov/ website.  This website has data available such as crime data which is updated daily.  Specifically we will be using the crime data located at URL: https://data.baltimorecity.gov/api/views/wsfq-mvij/rows.csv?accessType=DOWNLOAD

This data is not entirely complete and has many missing entries.  The data needs to be cleaned up so that its usable.   There is also a very large amount of data which prevents it from being loaded correctly on Maps, I will only include the data necessary for the analysis

## Venue Data (Eateries and Schools)
Foursquare is a service that provides crowdsourced information about various venues in a geographic format.  In this case we will be using the foursquare API to pull information about local Eateries, and Schools in Baltimore City.
