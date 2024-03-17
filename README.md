# Tableau-Challenge

Link to my Tableau Public account: https://public.tableau.com/app/profile/rohit.asopa/vizzes

Just to explain the dataset I used:

I downlaoded 6 individual csv files from the Citi Bike Data webpage.

They were:
June 2023, July 2023, August 2023 (The summer months)
as well as 
December 2023, January 2024, February 2023 (The winter months)

I then used pandas (jupyter notebook) to first individually join June, July and August, and export the whole dataset as a 'summer months' excel file 

I did the same with joining December, Jan and Feb, and exported it to a 'winter months' excel file.
I have added a folder with images of all the worksheets, dashboards and story, just incase there is any issue with Tableau Public.

I then joined both the summer and winter excel files on another jupyter notebook, and exported it as a new excel file. 

I uploaded this summer/winter combined excel file to Tableau, and this is the file I used for the visualisations 

All the relevant excel files and jupyter notebook files are in this Github repo 


Some findings from the data:
-almost double the amount of trips are taken in summer as in winter 
-peak hours don't change too much in summer v winter - the peak evening hour in winter is one hour earlier 
-the map of start destinations and graphs of 10 most popular start destinations is rather ambiguous. On one hand, the map seems to 
suggest that there is generally less of a cluster along the shore of the Hudson river in winter, perhaps due to the colder temperature, 
but on the other hand, Hoboken Terminal is proportionally more popular in winter months. Perhaps when people exit from their transportation to the 
Hoboken Terminal Hub, they prepare to immediately ride a bike to their next destination, rather than walk. 
-from the 'most popular places to end a journey' stat, as well as the average ride distance stat, we see that people take generally rather short trips. They may ride from 
the Hoboken Terminal a few miles inland, or down the coast of the river. The fact that the largest trip during both summer and winter periods was only 12.65 miles, suggests that
these CitiBikes are only used for short transportation, possibly as an alternative to taxis, Uber, or Bus.
