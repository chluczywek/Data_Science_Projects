# Campy Horror Movie Visualizations 
### Main question : How have Campy Horror Movies changed over the years?
### Definition of Campy: in the style of camp : absurdly exaggerated, artificial, or affected in a usually humorous way

![](https://github.com/chluczywek/true-philosopher/blob/master/Images/small.gif)
![](https://github.com/chluczywek/true-philosopher/blob/master/Images/option.gif)

### Popular Movies Include:
![](https://github.com/chluczywek/true-philosopher/blob/master/Images/evil_dead_1_poster_01%20(4).jpg)
![](https://github.com/chluczywek/true-philosopher/blob/master/Images/evil_dead_2%20(3).jpg) 
![](https://github.com/chluczywek/true-philosopher/blob/master/Images/51t2-nBruYL._SY450_.jpg)
![](https://github.com/chluczywek/true-philosopher/blob/master/Images/dead_alive.jpg)
![](https://github.com/chluczywek/true-philosopher/blob/master/Images/killer_clown.jpg)
## First Part - Web Scraping
The first part is to find the titles, release years, genres, and IMDB rating of all Campy Horror Movies. This information was found on [AllHorror.com](https://www.allhorror.com/subgenre/campy?order=release_date&order_dir=asc) search for campy movies. 
## Second Part - Parsing Data
The second part aims to parse data from AllHorror and [movies_metadata.csv](https://www.kaggle.com/rounakbanik/the-movies-dataset#movies_metadata.csv) to find more information about the Campy Horror Movies listed from AllHorror. This included: release date, revenue, budget, original language, tagline, popularity, etc.   
## Third Part - Data Analysis
The second part is to analyze the dataframe and observe correlation between variables. For example, are the movie awards correlated to the worlwide gross ? Does the more a movie is a liked, the more the casting is liked ? See the jupyter notebook file.

![](https://github.com/chluczywek/true-philosopher/blob/master/Images/sample.png)

As we can see in the pictures above, the imdb score is correlated to the number of awards and the gross but not really to the production budget and the number of facebook likes of the casting.
Obviously, domestic and worlwide gross are highly correlated. However, the more important the production budget, the more important the gross.
As it is shown in the notebook, the budget is not really correlated to the number of awards.
What's funny is that the popularity of the third most famous actor is more important for the IMDB score than the popularity of the most famous score (Correlation 0.2 vs 0.08).
(Many other charts in the Jupyter notebook)
