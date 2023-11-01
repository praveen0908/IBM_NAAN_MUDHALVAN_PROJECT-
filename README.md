# Netflix Originals Data Analysis

This project involves an analysis of a dataset containing information about Netflix Original films. The dataset includes details like movie titles, genres, premiere dates, runtime, IMDB scores, and the languages in which the films are available. In this README, you'll find information about the project, how to run the code, and a brief summary of the analysis.

## Table of Contents

- [Project Description](#project-description)
- [Dataset](#dataset)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Data Overview](#data-overview)
- [Data Analysis](#data-analysis)
- [Conclusions](#conclusions)

## Project Description

This project is a Python-based data analysis of Netflix Original films. It explores various aspects of the dataset, such as the distribution of movie runtimes, the languages in which movies are available, genres, and more. The analysis aims to provide insights and answer specific questions related to the dataset.

## Dataset

The dataset used in this project contains the following features:

- Title: Title of the film (Object)
- Genre: Genre of the film (Object)
- Premiere: Original premiere date (Object)
- Runtime: Runtime in minutes (int64)
- IMDB Score: IMDB scores (float64)
- Language: Languages currently available (Object)

## Prerequisites

Before running the code for this project, you should have the following libraries installed:

- pandas
- numpy
- seaborn
- matplotlib
- plotly.express
- plotly.graph_objects
- datetime
- statsmodels.api

You can install these libraries using pip:


```bash 
pip install pandas numpy seaborn matplotlib plotly statsmodels.
```

## Getting Started

To get started with this project, follow these steps:

Clone the repository to your local machine.
Install the required libraries as mentioned in the prerequisites.
Run the Jupyter Notebook containing the Python code.
Data Overview
The initial data overview section involves importing the dataset, checking for missing values, and performing data preprocessing. The dataset's structure and summary statistics are also displayed.

##Data Analysis
The data analysis section explores various aspects of the dataset, such as:

* Languages of movies lasting more than 2 hours.
* IMDB values of movies shot in the 'Documentary' genre between January 2019 and June 2020
* The genre of the English movie with the highest IMDB rating
* Average 'Runtime' of movies shot in 'Hindi'
* Categories of property 'Genre'
* Three most used languages in movies
* Top 10 Movies with the Highest IMDB Ratings
* Correlation between 'IMDB score' and 'Runtime'
* Top 10 'Genre' with the highest IMDB Score
* Top 10 movies with the highest 'Runtime' value
* The relationship between Film and Year
* The most used 'Genre' of each language
* Outliers in the dataset
* The results are presented in visualizations such as bar charts, pie charts, and line charts.

## Conclusions
The analysis provides insights into various aspects of Netflix Original films, including trends in genres, movie runtimes, and IMDB scores. It answers specific questions about the dataset and identifies outliers.

For any questions or further information, please feel free to contact Me @ praveemessi2530@gmail.com.

Happy coding!
