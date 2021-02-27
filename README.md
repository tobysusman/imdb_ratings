# imdb_ratings

This is a small bit of code which I created having come across it relatively often on r/DataIsBeautiful and it always appears to be taken down relatively quickly.  This tool will take a TV series and the number of series as input and produce a line chart showing the ratings of episodes in that series.

The function is relatively straightforward, you need to go on IMDB to the main page of the TV Show you are interested in, like this: https://www.imdb.com/title/tt0200276/

Then you need to input the maximum number of series, the function does not work for episodes which are not rated, so you may want to go to the final season listed on IMDB to confirm that there are episodes.  You can also give the image a title so it may look like this.
movie_ratings('https://www.imdb.com/title/tt0200276/', 7, '''West Wing''')

Please let me know any possible improvements, I think that I could probably include an until loop to go through each Season until it hits an error.
