# Udacity-Data-Analyst-Nanodegree
# Real World Data Wrangling with Python

### Date created

Jerry Liu created this project on January 1, 2024

## Description
In this project, you will apply the skills you acquired in the course to gather and wrangle real-world data with two datasets of your choice.

You will retrieve and extract the data, assess the data programmatically and visually, accross elements of data quality and structure, and implement a cleaning strategy for the data. You will then store the updated data into your selected database/data store, combine the data, and answer a research question with the datasets.

Throughout the process, you are expected to:

1. Explain your decisions towards methods used for gathering, assessing, cleaning, storing, and answering the research question
2. Write code comments so your code is more readable

## Problem Statement

With the rapid growth of esports, understanding the current overall trends is a fascinating endeavor. By analyzing the data from Esports Earnings 1998-2023 on Kaggle, we can quickly gain insights:

1. Top 10 Earnings by Game All Times
2. Top Genre Earnings All Times

#### **Dataset 1:** GeneralEsportData

I chose this dataset because I am curious about every esports game release day, and the data set contains every esports game's total prize in the tournament. We can easily find which game's tournaments have the largest prize pool.

Type: CSV File

Method: The data was gathered using the "Downloading files" method from [Kaggle](https://www.kaggle.com/datasets/rankirsh/esports-earnings/data?select=GeneralEsportData.csv.)

Dataset variables:

*   *Variable 1 GAME: Game name
*   *Variable 2 ReleaseDate: Release Date of game
*   *Variable 3 Genre: Genre of game
*   *Variable 4 TotalEarnings: Total prizepool allocated in tournaments
*   *Variable 5 OfflineEarnings: Amount of earnings allocated in Offline/Lan events
*   *Variable 6 PercentOffline: Percent of earnings coming from offline tournaments
*   *Variable 7 TotalPlayers: Total amount of players who received a prize
*   *Variable 8 TotalTournaments: Total amount of tournaments in the site

#### Dataset 2 HistoricalEsportData.csv

I chose this dataset because I am curious about historical esports data. In this file, we can find monthly data from 01/1998 to 10/2023 containing earnings for every game on the site.

Type: CSV File

Method: The data was gathered using the "Programmatically" method from  [Kaggle](https://www.kaggle.com/datasets/rankirsh/esports-earnings/data?select=GeneralEsportData.csv.)

Dataset variables:

*   *Variable 1 Date: Month
*   *Variable 2 Game: Game name
*   *Variable 3 Earnings: The earnings from the tournaments
*   *Variable 4 Players: The player who participate in the tournaments
*   *Variable 5 Tournaments: The number of tournaments held


## Summary of Main Findings:

###  Top Earnings by Game All Times

After reviewing the analysis charts, it was surprising to discover that Dota 2's global popularity may not have surpassed that of LoL. Moreover, Dota 2 was released later than LoL, yet its overall prize pool is significantly higher. Some discussions suggest that this might be due to LoL adopting a franchise system, which may result in a lower prize pool than in other games. Another noteworthy point is that Fortnite, released in 2017, currently holds the second position, highlighting its immense impact.

### Top Genre Earnings All Times

The prize money for MOBA games far exceeds that of other genres, totaling 591 million USD. This also indicates the immense popularity of this genre, with three out of the top five games being MOBAs. The presence of CS-related series in the top ranks is expected, given their established status among players. However, the most impressive category is Battle Royale, with three games from this genre making it into the top ten. Notably, all three of them were released in 2017, showcasing the rapid growth they've experienced. This category has a high chance of surpassing the second-ranking FPS in the future, as their gaming dynamics share some similarities.