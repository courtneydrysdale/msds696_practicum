# Music and Lyrics: Clustering Pop Songs by Theme and Decade
#### Courtney Drysdale
##### Regis University - MSDS 696 Practicum II Fall 2025

In this project, I analyzed pop song lyrics and audio features to determine common themes and trends within decades. 
I wanted to see if there are different features that are obvious by decade or if there are commonalities over time. 
I used text analytics tools to cluster the lyrics to look for themes within each decade. I also used data visualization 
to look at commonalities of features within time periods. This information could be used for entertainment based business 
decisions, like looking for new artists that may be trending or choosing songs for film or television or marketing. 

## Dataset Introduction

For this project, I combined two datasets from Kaggle:

- [5 million song lyrics from Genius](https://www.kaggle.com/datasets/carlosgdcj/genius-song-lyrics-with-language-information)
- [1.2 million song features from Spotify](https://www.kaggle.com/datasets/rodolfofigueroa/spotify-12m-songs)

After merging the datasets and limiting to only pop songs from the 1970s-2020, I had about 46,000 rows, each representing a song.

## Project Overview

After cleaning the text, I clustered the song lyrics in each decade to find themes. I looked at the top 10 words in each cluster
and created a WordCloud of each decade and the lyrics overall. 

<p align="center">
<IMG SRC = "https://github.com/courtneydrysdale/msds696_practicum/blob/main/images/lyrics_wordcloud.png">

<IMG SRC = "https://github.com/courtneydrysdale/msds696_practicum/blob/main/images/songs_per_decade.png" width="500"></P>
