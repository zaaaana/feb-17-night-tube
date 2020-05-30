# Night Tube Usage in February 2017
### An individual visualisation showing the monthly number of passengers between August 2016 and February 2017.

![alt text](https://i.ibb.co/BySCxyk/tube-SS.png "Logo Title Text 1")

The visualization created aims to highlight the flow of Night Tube passengers across the London Underground Tube network, for the first 6 months of Night Tube Serevice. The idea for this visualization takes inspiration from Olivier O’ Brien’s [‘Tube Heartbeat](https://oobrien.com/2016/08/tubeheartbeat/),’ which highlights the motion of passenger entering, alighting and interchanging within the London Underground during weekly daytime and evening services. 

The concept of night tube was introduced in 2014, with services starting at the end of 2016. Central and Victoria were the first accessible lines From August 2016, followed by service on the Jubilee line in October 2016, Northern in November 2016, and lastly, the Piccadilly line on December of 2016. This interactive visualization will show the popularity of the service as each line is introduced in the timeframe.

Night tube travel data was taken from the Transport for London (TfL) website, in the form of a CSV file. This file consisted of total passenger data from the first night tube service in August 2016, up until the first week of February 2017. For each station, the number of passengers who have either entered or exited was recorded for half-hour intervals between 12:30 a.m. and 6:00 a.m. for each Friday and Saturday during which the night tube was active. This data was categorized according to station and months, in order to highlight the cumulative monthly passenger data.

While the dataset used is able to highlight the passenger flow over the weekends, there are a few limitations with regards to the values included. Since the passenger values are an aggregate based on station usage, this means that it was not possible to determine what lines were of higher popularity at specific stations with interchange access during nighttime hours. In addition to this, data could not be filtered to specify what proportion of passengers were entering, alighting or interchanging during these times. Furthermore, in cases where less than 5 passengers accessed a station within any half hour, values were recorded as “3 passengers” as a benchmark.

An interactive map was created using HTML and JavaScript, with basemaps and tilesets created in Mapbox. The edited CSV data was edited via Python (Pandas) to classify each station and timeframe accordingly. 
