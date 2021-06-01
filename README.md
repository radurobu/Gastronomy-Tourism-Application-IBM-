# Capstone Project - Gastronomy Tourism Appliaction
# Applied Data Science Capstone by IBM/Coursera
# Gastronomy Tourism Appliaction

Introduction: Business Problem 
What is Gastronomy Tourism??

Food is now a main motivation for travelers choosing their destinations. Travelers are spending more time and money on unique food and beverage experiences. We have seen a global increase in food tour companies, food and beverage focused events and food and beverage experience focused marketing efforts.

But can we use machine learinig to help improve the gastronomy tourism entusiasts experiance?
I am a burger enutuziast, and i am intrested in visiting some nice buger specific venues and also have a nice trip in some of Europes capitals. Can we come up with a data science aproach that can help me answer my question: in wich cities can i find the best burger joints? A nice traveling location in my case should have lots of cheap and high rated burger venues and also should be as close as possible to my hometown Bucharest.

By developing a data science framework to answer my question, maybe we can further help other gastronomy tourists whith different intrests (lets say pizza lovers) find theyr next vacation location.

Methodological approach:

- Phase1: I will scrap 'http://techslides.com/list-of-countries-and-capitals' to get the latitude and longitude coordinates for all Europe's capital cities

- Phase2: Next, I will get the venues near the capital city centers of Europe

- Phase3: Extract other relevent info (likes count, photos count , price cateqory, rating etc.) using the forsquae app

- Phase4: I will prepare the data for the clustering phase

- Phase5: Clustering the citties using the venu info we extracte from foresquare

- Phase 6: Map vizualization usnig Folium
