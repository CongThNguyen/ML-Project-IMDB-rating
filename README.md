# Machine Learning in Python - Project 1

## Data

We will be using data about the American TV show The Office. These data are provided as `the_office.csv` in this repository and are meant to give you a reasonable starting point for this assignment. The dataset includes the following columns:

* `season` - Season number of the episode

* `episode` - Episode number within a season

* `episode_name` - Episode name

* `director` - Episode director(s), names are separated by `;`

* `writer` - Episode writer(s), names are separated by `;`

* `imdb_rating` - Episode rating on IMDB

* `total_votes` - Number of ratings for episode on IMDB

* `air_date` - Original air date of episode

* `n_lines` - Number of spoken lines in episode

* `n_directions` - Number of lines containing a stage direction

* `n_words` - Number of dialog words in episide

* `n_speak_char` - Number of different characters with spoken lines in episode

* `main_chars` - Main characters appearing in episode (main characters were determined to be characters appearing in more than 1/2 of the episodes)

These data were derived from the data available in the [`schrutepy`](https://pypi.org/project/schrutepy/) package. The package provides a data frame containing the entire text transcripts from all episodes of the show. 



## Assignment

For the purposes of the project, consider yourself a Data Scientist contractor who has been hired by NBC Universal to advise on the creation of a special reunion episode of The Office. Your employers are particularly interested in understanding what made some episodes more popular than others. As such, your task is to use these data (or any other) to build a predictive model that captures the underlying relationships between these features and the audience ratings, and then use the insights you gain from this model to advise what NBC Universal should do to produce the highest rated reunion episode possible.

In other words, you need to develop an *understandable* *validated* model for The Office's `imdb_rating` as the outcome of interest using features derived from the data provided and any additional sources you would like. It is important that this model be accurate **and** reliable and any conclusions you draw well supported and sound. We explicitly do not want a blackbox model - you should be able to explain and justify your modeling choices and your model's predictions.

Your model may use as few or as many of the provided features, and you may transform and manipulate these features in any way that you want to generate additional features. 

We have covered a number of models and modeling approaches in the lectures and workshops and you should explore a variety of different approaches for this particular task. However, your ultimate goal is to deliver a **single** model. These are competing interests and it is up to you to find a reasonable balance between the two - some of your marks will be based on how well you accomplish this.



## Required Structure & Formatting

We have provided a templated Jupyter notebook called `project1.ipynb` which includes the required sections along with brief instructions on what should be included in each section. Your completed assignment must follow this structure - you should not add or remove any of these sections, if you feel it is necessary you may add addition subsections within each. Please remove the instructions for each section in the final document.

All of your work must be contained in the `project1.ipynb` notebook, we will only mark what is included in this file.

Our expectation is that most projects will be roughly 10-15 pages in length (text & figures, excluding code). Your notebook must include all of your work, but make sure that you are only retaining required components, e.g. remove unused code and figures (if a figure is not explicitly discussed in the text it should not be in the final document).

Overall, your project will be partially assessed on your organization / presentation of the document - it should be as polished and streamlined as possible. We highly recommend that you check the appearance of your rendered PDF before submitting, as its appearance can differ significantly from the notebook.

## Group work

This project is completed by a team of up to 4 students.

