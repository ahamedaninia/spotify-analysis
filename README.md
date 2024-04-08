# Spotify -- What makes a good song, great?

The initial purpose of this project was to practice pulling data from different sources (API, flat files, and scraping data from a website), and I decided to have fun with it and see what makes a good song, great? These data sources include variables like beat, rpm, key, how many playlists they've been added to, how long were in they in top 10, etc. 

### **Project Subject:** Using various sources to look at the Spotify charts and top music charts, we will analyze the different relationships and aspects of a song that may correlate to it rising to the top charts. 

We will be using three different data sources to analyze this idea:

### **Data Sources**

#### API: [APIList](https://apilist.fun/api/spotify-web)

This API looks up metadata about artists, tracks, and albums

#### Flat file: [Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023)

“This dataset contains a comprehensive list of the most famous songs of 2023 as listed on Spotify. The dataset offers a wealth of features beyond what is typically available in similar datasets. It provides insights into each song's attributes, popularity, and presence on various music platforms. The dataset includes information such as track name, artist(s) name, release date, Spotify playlists and charts, streaming statistics, Apple Music presence, Deezer presence, Shazam charts, and various audio feature” 

#### Website (Table): [Wikipedia](https://en.wikipedia.org/wiki/List_of_Billboard_Hot_100_chart_achievements_and_milestones)

This wikipedia link contains several different tables that may be of use in this study, such as Top 10 songs of all time (1958–2021), Top 10 artists of all time (1958–2021), Most weeks at number one, Most weeks at number two (without hitting number one), and much more.


These three data sources each contain information about Spotify, specifically about the artists and songs that do the best. When looking at them altogether, we can form relationships between the different datasets according to what information they can provide about the top songs released. 

In each dataset, I will use about 5 different transformations on each one. I will then combine then into an SQLlite database, and use PowerBI to visualize the data in a few different ways. 

## Why is this useful?
In theory, an up and coming artist can use the results of this project to gain an understanding of how to bring their new music up the charts. In reality, that most likely is not going to happen, but this was a great exercise in pulling data from these different sources and combining them into an SQLite database. It is great practice for working with data from different sources.

## How can YOU get started with this project
Choose a subject of interest to you, and see what three different sources you can obtain the data from. I recommend Wikipedia for your web source, though for a challenge you can try other websites as well, Wikipedia has easy tables to scrape from. See how you can challenge yourself to combine them seamlessly, and what can you learn from your data.

## Maintenance
This project was completed as part of my coursework to achieve my Masters in Data Science at Bellevue University. It is not currently being maintained, but revisited to be updated with my new skills I acquire.
