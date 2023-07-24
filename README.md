<img src="./images/vecteezy_microsoft-logo-on-transparent-background_14018578.jpg" alt="Microsoft Logo" width="300">

# Exploratory Data Analysis For Proposed Microsoft Studio

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
* I accurately decribe the dataset about which movie genres are doing the best at the box office
* I generate useful recommendations about types of films the studio should create

## Understanding Data
The data sources for this data science project will be:

* The bom.movie_gross.csv dataset, which contains information about the gross earnings of movies from [Box Office Mojo](https://www.boxofficemojo.com/).
* The title.basics.csv dataset, which contains information about the basic details of movies from [IMDB](https://www.imdb.com/).
* The title.ratings.csv dataset, which contains information about the ratings of movies from [IMDB](https://www.imdb.com/).

The combined dataset has the following variables:
* **tconst**- movie unique identifier code.
* **primary_title**- movie title
* **original_title**- movie title in the native language which the movie was shot at. 
* **start_year**- year the movie release year
* **runtime_minutes**- movie length in minutes 
* **genres**- film genre such as Comedy 
* **averagerating**- the weighted average of all the individual user ratings
* **numvotes**- the number of votes the movie has received
* **foreign_gross**- foreign gross revenue for a movie 
* **domestic_gross**- domestic revenue for a movie

## Methods

This project uses exploratory data analysis.

## Conclusions

* Movie Releases: The period between 2014 and 2016 witnessed the highest number of movie releases, with 2016 recording the peak. This indicates a potential trend of increased production during these years.

* Movie Genres: Action movies were the most frequently released genre, followed by Comedy and Drama. It shows that the audience's preference leaned towards action-oriented content during this period.

* Revenue by Genre: Family genre movies generated the highest revenue, followed by adventure, with Action movies coming in third. This suggests that family-oriented and adventurous films tend to perform well financially.

* Adventure Genre Revenue: The adventure genre consistently earned more revenue over the years, indicating a sustained popularity of adventurous themes among the audience.

* Studio Performance: BV (Buena Vista), as the top studio by revenue, achieved high ratings and earnings. Fox came second with slightly lower ratings, while P/DW (Presidents/DreamWorks) had relatively lower earnings despite better ratings.

* Buena Vista's Performance: BV demonstrated high revenues in 2016 and 2017, and its revenue performance has generally been impressive across the years.

### Recommendations

* Focus on Popular Genres: Based on the observations of high revenue generation, studios should continue producing movies in genres that have historically performed well, such as family-oriented, adventure, and action films.

* Invest in Adventure Genre: Given the consistent revenue generation of adventure films, studios should consider allocating more resources to produce captivating adventure-themed content to cater to the audience's interest in this genre.

* Quality over Quantity: Although the years 2014-2016 saw high movie releases, it is crucial for studios to maintain a balance between quantity and quality. Prioritize creating high-quality content to enhance the chances of success and positive audience reception.

* Strengthen Ratings and Revenue Balance: Studios that aim to achieve both high ratings and revenue should pay attention to the content's quality and market appeal. A focus on engaging storytelling, well-developed characters, and appealing themes can help strike the right balance.

* Strategic Scheduling: Consider strategic release schedules to maximize revenue potential. Identify periods when the audience demand is high and competition is relatively low for specific genres.

* Long-Term Planning: Learn from the success of BV, which consistently performed well across the years. Studios should adopt a long-term planning approach, nurturing franchises and building a loyal fanbase to sustain revenue growth over time.

* In summary, studios should leverage the popularity of action, adventure, and family genres, while also focusing on producing high-quality content to achieve both strong ratings and revenue. Strategic planning and careful attention to audience preferences can contribute to long-term success in the dynamic movie industry.


## For More Information

See the full analysis in the [Jupyter Notebook](./movie-EDA.ipynb) or review this [presentation](./movie-EDA.pdf).

For additional info, contact Dominic Muthiani Muli at [dominic.muli@student.moringaschool.com](mailto:dominic.muli@student.moringaschool.com)

## Repository Structure
```
├── data
├── images
├── movie-genre-analysis.ipynb
├── movie-genre-analysis.pdf
└── README.md
```