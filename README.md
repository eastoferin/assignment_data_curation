# assignment_data_curation
Top 500 Artists by Streaming Data on Spotify

This file contains the work for my Coding Assignment: Data Curation and Analysis for I 310D.

Overview:
This project entailed webscraping a website reporting streaming statistics for the top artists on Spotify. I utilized the chart on the following page: https://kworb.net/spotify/artists.html

Goal:
My goal for this project involved determining if there was a correlation between the amount of views the top artists got on tracks which were either solely their own, theirs with a feature artists, and them featuring on another artist's track. I wanted to see if there were outliers in the top 500 who became most streamed artists through working primarily with others rather than on their own. I found this out through scraping the data and turning it into certain graphical visualizations.

API Documentation:
Beautiful Soup: https://beautiful-soup-4.readthedocs.io/en/latest/
Pandas: https://pandas.pydata.org/docs/
NumPy: https://numpy.org/doc/
Matplotlib: https://matplotlib.org/stable/index.html
Requests: https://docs.python-requests.org/en/v2.0.0/api/#main-interface


License of Data:
This data was not mine. I took it from this website (https://kworb.net/spotify/artists.html). Additionally, they took this data from Spotify itself. Nothing on the website indicates if the data is protected and not for use within projects; however, I utilized solely for a course at UT Austin and not for my own gain.

Data Type & Description:
Artist: This is a string data type which showcases the name of the artist in the charts
Streams: A float data type which holds the total number of streams this artist has garnered of all time.
Daily: A float data type which showcases the number of daily streams that the artists earns on Spotify
As lead: A float data type which shows how many streams the artist has gained of tracks in which they are the lead artist, but there is also a featured artist.
Solo: A float data type which showcases the number of streams the artist has on a track which is only credited to them.
As Feature: A float data type which shows the number of streams the artist gained of tracks in which they are the featuring artist. 


Known Issues & Biases in Collection:
There is a warning at the top of the chart indicating that their may be glitches present within the data as the chart is still under construction. Although all of the information looked correct visually, there might be some errors which are factored into my database and the subsequent visuals. Additionally, I'm not sure how often the chart is updated which might effect the accuracy of the data.
