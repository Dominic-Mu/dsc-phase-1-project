<img src="./images/vecteezy_microsoft-logo-on-transparent-background_14018578.jpg" alt="Microsoft Logo" width="300">

# Movie Genre Analysis For Proposed Microsoft Studio

**Author**: [Dominic Muthiani Muli](mailto:dominic.muli@student.moringaschool.com)

## Project Overview

[Microsoft Corporation](https://www.microsoft.com/en-us/) is a multinational computer technology corporation that develops, licenses, and sells computer software, consumer electronics, and personal computers. It is headquartered in Redmond, Washington. The company was founded on April 4, 1975, by Bill Gates and Paul Allen in Albuquerque, New Mexico. 

This project analyses movie genre ratings and gross earnings to offer Microsoft Corporation insights about movies for the proposed new original movie studio.

## Business Problem
<img src="./images/Clapper_board_Clapper-board.jpg" alt="Movie" height="200">

Microsoft plans to venture in original video content creation. The head of Microsoft's proposed movie studio wants to know what genres of films are currently performing best at the box office. They need this information so that they can focus on creating films that are likely to succeed.

## Objectives
* Identify the best performing movie genres at the box office.
* Generate recommendations for the types of films that Microsoft's proposed movie studio should create.

## Metric of Success
The project will be considered successful if:
* I accurately make predictions about which movie genres are doing the best at the box office
* I generate useful recommendations about types of films the studio should create

## Understanding Data
The data sources for this data science project will be:

* The bom.movie_gross.csv dataset, which contains information about the gross earnings of movies from [Box Office Mojo](https://www.boxofficemojo.com/).
* The title.basics.csv dataset, which contains information about the basic details of movies from [IMDB](https://www.imdb.com/).
* The title.ratings.csv dataset, which contains information about the ratings of movies from [IMDB](https://www.imdb.com/).

The combined dataset has the following variables:
* **tconst**- movie unique identifier code.
* **primary_title**- movie title such 
* **original_title**- movie title in the native language which the movie was shot at. 
* **start_year**- year the movie started airing
* **runtime_minutes**- movie length in minutes 
* **genres**- film genre such as Comedy 
* **averagerating**- the weighted average of all the individual user ratings
* **numvotes**- the number of votes the movie has received
* **foreign_gross**- foreign gross revenue for a movie 
* **domestic_gross**- domestic revenue for a movie

## Methods

This project uses exploratory data analysis.

## Results



## Conclusions



### Recommendations


## For More Information

See the full analysis in the [Jupyter Notebook](./movie-genre-analysis.ipynb) or review this [presentation](./movie-genre-analysis.pdf).

For additional info, contact Dominic Muthiani Muli at [dominic.muli@student.moringaschool.com](mailto:dominic.muli@student.moringaschool.com)

## Repository Structure
```
├── data
├── images
├── movie-genre-analysis.ipynb
├── movie-genre-analysis.pdf
└── README.md
```