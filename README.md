# Coursera_Capstone
IBM Data Science Capstone Project Work


This capstone project has been submitted as part of the requirements for completion of the IBM Data Science Professional Certificate on Coursera. In general, this project encompasses a series of Data Science techniques, including, but not limited to, Web Scraping (using BeautifulSoup and Requests), Data Cleaning, Data Wrangling and Machine Learning (K-Means clustering algorithm)

# The Battle of Neighborhoods


## Introduction: Business Problem <a name="intro"></a>

This project deals with discussing the neighborhoods of **Dallas**. This would specifically help Business people planning to start **Restaurants, Hotels, etc.** in Dallas, USA.

The **Foursquare API** is used to access the venues in the neighborhoods. Since, it returns less venues in the neighborhoods, we would be analysing areas for which countable number of venues are obtained. Then they are clustered based on their venues using Data Science Techniques. Here the **k-means clustering algorithm** is used to achieve the task. The optimal number of clusters can be obtained using **silhouette score** metrics. **Folium visualization library** can be used to visualize the clusters superimposed on the map of Dallas city. These clusters can be analyzed to help small scale business owners select a suitable location for their need such as Hotels, Shopping Malls, Restaurants or even specifically Indian restaurants or Coffee shops.

The major **Target Audience** would be small-scale business owners and stake holders planning to start their business at a location in Dallas. This project would help them find the optimal location based on the category of their business such as,

*	What is the best location to start a new hotel in Dallas with restaurants around?
*	Which area is best suitable for opening a Shopping Mall in Dallas?


Purpose of this project was to analyze the neighborhoods of Dallas and create a clustering model to suggest personals places to start a new business based on the category. The neighborhoods data was obtained from an online source and the Foursquare API was used to find the major venues in each neighborhood. But we found that many neighborhoods had less than 10 venues returned. In order to build a good Data Science model, we filtered out these locations. The remaining locations were used to create a clustering model. The best number of clusters i.e. 8 was obtained using the silhouette score. Each cluster was examined to find the most venue categories present, that defines the characteristics for that particular cluster. 

A few examples for the applications that the clusters can be used for have also been discussed. A map showing the clusters have been provided. Both these can be used by stakeholders to decide the location for the particular type of business. A major drawback of this project was that the Foursquare API returned only few venues in each neighborhood. As a future improvement, better data sources can be used to obtain more venues in each neighborhood. This way the neighborhoods that were filtered out can be included in the clustering analysis to create a better decision model.

## Thank you!

I hope you found the project useful and interesting. This project was deveoped for the **Applied Data Science Capstone** as part of the **IBM Data Science Professional Certificate** provided through Coursera. Feel free to fork or download this project for your requirements.

