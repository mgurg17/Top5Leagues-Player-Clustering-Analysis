# Top5Leagues Player Clustering Analysis

This is a project focused on clustering players into groups based on their individual stats rather than position. Then there is analysis into team performance based on the top 11 players' (by minutes played) assigned clusters. Finally, there is an attempt to glean insight from player wages, though none is revealed.

The limitations of this are the fact that it is difficult to determine the most representative number of clusters, missing players due to NaN values in their statistics necessitating their removal, and the difficulties in adjusting for player quality. However, this study does show promise in finding new ways of comparing and scouting players based on their indicidual contributions.

The data was scraped from Fotmob.com and fbref.com, and the analysis utilized various Python libraries: Pandas, NumPy, Selenium, sklearn, Matplotlib, and statsmodels. 
