## Song Lyrics Analysis
Comparing word frequencies from top 100 songs per year.

Using LyricsgeniusAPI.
Top 100 chart data from officialcharts.com.

------
Started this project in midst of final year university deadlines...
So unfortunately I don't have the time to finish it at this time.

Below are the most immediate actions still uncompleted:

#### TODO
- [ ] API details in environment variables
###### Cleaning
- [ ] Remove all words before first instance of "Lyrics"
- [ ] Remove all substrings "4Embed"
- [ ] Remove other common words not included in nltk stopwords?
- [ ] Remove punctuation (not apostrophes)
- [ ] Apply cleaning to all lyrics (use df.apply?)
###### Analysis
- [ ] Apply count to all cleaned lyrics
- [ ] Plot results
