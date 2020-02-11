# IN PROGRESS - Sports-Analytics-Personal-Project---Michigan-Basketball
Sports analytics personal project examining the 2018-19 University of Michigan Men's Basketball Season in an attempt to determine 
which player was most valuable to the team in important situations.

Using the metric of Expected Win Probability Added, I will be examining every play from the season that occurred within the last 
five minutes of a game in which the score differential is 6 points or less (two-possession game). By examining the eWPA, which will be referred to as "clutch score", for each player during these situations throughout the season, I can attempt to determine which player had the largest positive effect on eWP during "clutch" situations. For this project, I will only be examining the six players on Michigan's roster who averaged more than twenty minutes played per game.

Play by play data was obtained from sports-reference.com

https://www.sports-reference.com/cbb/

Expected Win Probabilities Added per Play Type was obtained from inpredictable.com

https://www.inpredictable.com/2014/03/measuring-clutch-play-in-nba.html

Although these probabilities were calculated for NBA games, this project relies on the assumption that the eWPA for college basketball games are relatively similar. Because they were not listed on the the website, I added my own "clutch score" value for an assist and one for all situations of drawing a foul.

Other References:

https://medium.com/@smehta/scrape-and-create-your-own-beautiful-dataset-from-sports-reference-com-using-beautifulsoup-python-c26d6920684e

https://codeburst.io/web-scraping-101-with-python-beautiful-soup-bb617be1f486
