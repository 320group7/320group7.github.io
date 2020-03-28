# 320group7.github.io
Data Science Project
# STOR 320 PROJECT PROPOSAL
 GROUP 7: Celia Collias (Captain), Liam Laughner (Engineer), Ashka Shah (Doctor), & Naixuan/Lauren Wang (Emissary)

### PROPOSAL QUESTIONS/METHODS AND SCOPE

#### Topic: 
  * The Oscars

#### Motivation:  
  * Our project seeks to undercover possible biases and trends—social, economic, institutional, or otherwise—portrayed by the Oscars that reflect the evolution of entertainment preference, social justice, and cinematic accomplishment over time. To complete this analysis, we collected datasets with variables of year, film title, genre, movie budget, box office sales, award category, nominee, number of nominations, and winning status.

#### Questions:

1. How do box office sales differ from Oscar “Best Actor” winners and “Best Actress” winners?
   * Method: Create two separate summary data tables for each gender. First, group by “Best Actor” then apply count, sum, median, and mean to box office sales. Second, repeat for “Best Actress”. Use scatterplots and histograms to display outcomes with both “Best Actor” and “Best Actress” variables overlaid.

2. How does budget differ from Oscar “Best Actor” winners and “Best Actress” winners?
   * Method: Create two separate summary data tables for each gender. First, group by “Best Actor” then apply count, sum, median, and mean to budget. Second, repeat for “Best Actress”. Use scatterplots and histograms to display outcomes with both “Best Actor” and “Best Actress” variables overlaid.

3. How does the movie genre differ from Oscar “Best Actor” winners and “Best Actress” winners?
   * Method: First, group by movie genre. Then select only the best actor and actress winners and use a count function to see how common each genre is. Use scatterplots and histograms to display outcomes to see trends over time.

4. How do budget and box office sales differ for Oscar “Best Picture” nomination winners and losers?
   * Method: First, group by “Best Picture” then apply count, sum, median, and mean to budget, box office sales, and winner status. Use scatterplots and histograms to display outcomes.

5. How do the mean statistics for the following variables differ between nominee winners and losers: budget, box office sales, and genre?
   * Method: Create two separate summary data for both “winners” and “losers” category. First, group by “winners,” then apply count, sum, median, and mean to budget, box office sales, and genre. Second, repeat for “losers”. Use scatterplots, boxplots, and histograms to display outcomes.

6. Which variables are the most effective for predicting an Oscar winner amongst the nominations for each main award category?
   * Method: Use “bestglm” package. Analyze forward and backward stepwise regression. Then show graphs and correlation summary statistics. Also check which variables have the strongest correlation effect on the data using clustering and graphs to visually demonstrate. Use clustering and look at principal components for the variables.  Use outcomes to make predictions.

### DATA AND SOURCES 
a. https://datahub.io/rufuspollock/oscars-nominees-and-winners#resource-data 
   * Years: 1927- 2017
   * Variables: Year, Category, Winner, Entity (Recipient)
   * Source: Oscars website
b. https://cs.uwaterloo.ca/~s255khan/oscars.html and https://github.com/titubeta/oscars 
   * Years: 1927 - 2015
   * Variables: Year, Rating, Name, Movie, #Nominations, Duration, Genre1, Genre2, Metacritic Rating, Synopsis (not useful), 
The best actresses nominations have lots of NAs. Three main categories: Best Actor, Best Actress, Best director, and Best Motion Picture. Variables are all the same. 
   * Source: Shehroz Khan, IMDB, and Oscars website
c. https://www.aggdata.com/awards/oscar 
   * Years: 1927-2010
   * Variables: Year, Category (as in award category), Nominee, Additional Info, Won? 
   * Source: Oscars website
d. http://awardsdatabase.oscars.org/ 
   * Years: 1927-2019
   * Variables: Year, Film Title, Nominee, Award Category
   * Source: Original Oscars Database
e. http://aaspeechesdb.oscars.org/ 
   * Years: 1927-2019
   * Variables: Year, Film Title, Nominee, Award Category
   * Source: Original Oscars Database
f. https://www.kaggle.com/danielgrijalvas/movies
   * Years: 1986-2016
   * Variables: Budget, Company, Country, Director, Genre, Gross Revenue, Name, Rating, Released, Score, Star, Votes, Writer, Year, Award
   * Source: IMDB
g. https://data.world/crowdflower/academy-awards-demographics
   * Years: 1927-2014
   * Variables: Year, Golden (if they won or not), Birthplace, Date of Birth, Ethnicity, Race, Religion, Sexual Orientation, Movie, Person
   * Source: Justin Tenuto, Silk.co (no longer exists!) 
h. http://www.awardsandshows.com/features/awards-categories-1.html
   * Years: 1991-2009
   * Variables: Year, Winner, Film (broken down by each award category)
   * Source: Awards and Shows
 
### RELATED WORK

  Previously, projects on websites like FiveThirtyEight have predicted exact winners for the Oscars a couple of weeks before the ceremony takes place (for example see https://fivethirtyeight.com/features/oscars-2018-here-are-our-final-predictions/). Our project differs from these projects because we will provide a general prediction of the demographics of who will win the following year rather than a specific person along with the characteristics of movies that will win an award the following year.
     
  Other projects have sought to verify, categorize, and quantify the lack of diversity associated with the Oscars (for example see https://fivethirtyeight.com/features/hollywoods-diversity-problem-goes-deeper-than-the-oscars/). We plan to do the same but dive deeper and analyze diversity issues for specific awards by giving a breakdown of the demographics of previous award recipients.
     
  Some projects look at prediction factors of who should win against who will actually win based on previous wins (for example see https://www.newyorker.com/culture/the-front-row/oscars-predictions-2020-the-gulf-between-who-should-win-and-who-will). Our project differs from this by just focusing on who will win based on previous trends against other nominees. We will not make claims of who should win in our project. Our project will reveal underlying patterns of who will win based on variables like budget, box office sales, and genre.



##### END OF PROPOSAL
