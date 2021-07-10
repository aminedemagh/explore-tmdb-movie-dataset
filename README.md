# Explore TMDb Movies Dataset

## Date created
This project was created on 2021-02-09.

## Description

This project explores the movie dataset of [TMDb](https://www.themoviedb.org/) which is a popular, user editable database for movies and TV shows. The goal is to identify the features that can best predict the return on investement of a movie.

This work was made to complete an assignement for the [Udacity Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002).

## Files used

`Explore TMDb Movie Dataset.ipynb` : The jupyter notebook for wrangling and analyzing the data.

`tmdb-movies.csv` : The movie dataset.

There is also another file that is not included in the repository `MovieData.csv`. This file was used to fill the missing values for the revenue of the movies. It was provided by [The Numbers](https://www.the-numbers.com/), a company that tracks financial movie data. Since it was a proprietary dataset, I could not share it on Github. However, you can obtain it for free by simply filling their [form](https://www.opusdata.com/). They will send you an email with a dropbox link and a password to download it. 

## Installation

To run the notebook, you will need `python`, `numpy`, `pandas`, `matplotlib`, `urllib`, `json`, and `seaborn` installed. You can download all these libraries individually or with [Anaconda](https://www.anaconda.com/), a python distribution with a focus on data science. If you’re interested in Anaconda you can follow their [installation guide](https://www.anaconda.com/distribution/).

You will also need to get an API key for [OMDb API](https://www.omdbapi.com/). It is a web service that offers a great wealth of information about movies. It is used in this project to fill missing values. You can get a free key by [creating an account](https://www.omdbapi.com/apikey.aspx)  and you will receive it at the email address that you used for registration. 

## Dataset

This dataset contains information about 10866 movies and has 21 columns. The missing values were filled using both OMDb API and `MovieData.csv`. The columns that were selected for analysis are : `id`, `popularity`, `budget`, `revenue`, `original_title`, `runtime`, `genres`, `release_date`, `vote_count`, `vote_average`, `release_year`, and `roi`

## Credits

Thanks to the [One Million Arab Coders' initiative](https://www.arabcoders.ae/) for offering me a chance to learn data science.

Thanks to [Udacity](https://www.udacity.com/) for their great content.

Thanks to [TMDb](https://www.themoviedb.org/) for providing their data to students.

Thanks to [OMDb API](https://www.omdbapi.com/) for their free API keys.

Thanks to [The Numbers](https://www.the-numbers.com/) for sharing their data.