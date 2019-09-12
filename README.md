# Correlation of "Citizens' Evaluations About Foreign Movies" in The Shade of "Governments' Official Policy"
## A Study of in The Example of US Citizens Voting about Iranian and Russian Movies

My theoretical hypothesis is; “__The evaluations of citizens’ voting about foreign movies are not influenced by the governments' official policy__”.
 
Because of the exhaustive hypothesis, it is not easy to collect data. So I decided to restrict the hypothesis in the example of the US and its politically affair tense countries; Russia and Iran. I used “the ratings of US citizens about Iranian and Russian movies” and “the ratings of Non-US people about Iranian and Russian movies” data from IMDB.
 
We need two data, which are the rating data of US citizens and Non-US people about Iranian and Russian movies. At IMDB, these data exist for every movies. We can see that 15.115 Russian and 6.923 Iranian movies exist as of 08.09.2019. To prevent the noise, to avoid the falsity and to reach the healthy result; only the movies were taken into account,  which has 5000 or more votes. As a result, our population decrease to “the rating data of 99 (37 Iranian, 62 Russian) movies”. So, I don’t need to take sample and studying with the population data.

## As a result;
- 0.9233691632171431 Pearson's r-value obtained with the data of the US and Non-US Ratings About Iranian Movies.
- 0.96001528325696 Pearson's r-value obtained with the data of the US and Non-US Ratings About Russian Movies.
- This strong correlation value supports the hypothesis.


## Used Libraries
- The data was scraped (collected) from imdb.com with Python BeautifulSoup library.
- Mean, standard deviation (std) and p-value of the data were calculated by Python NumPy library. 
- Visualizing the result by Python SeaBorn library.

