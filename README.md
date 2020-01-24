# TMDb-Movie-Data
This project dives into a dataset provided by The Movie Database (TMDb) on thousands of different movies. 
The various properties associated with movies are visualized using multiple different plots to identify patterns in the data
and answer the key question.

## Key Question

_What properties are associated with highly rated movies?_

## Data Wrangling & Cleaning

The dataset is loaded into a dataframe from the file called *tmdb-movies.csv*. The data is inspected and cleaned for analysis. Duplicate rows and irrelevant columns are removed, variables are renamed, and null values are dropped. 

## Exploratory Data Analysis

The first step in exploring the data and uncovering insightful conclusions related to the key question is to define the question. _Highly rated_ can be defined in many ways using this dataset since two columns can represent this: 'vote_average' and 'popularity'. To conduct further analyses on this metric, the more sufficient column must be chosen to define *highly rated*. In order to choose this, box plots for both are visualized which indicate that 'vote_average' is more evenly distributed and thus easier to decipher and work with. Moving forward, all analyses will be done against this column.  

## Tools

* tmdb-movies.csv
* Python
* Jupyter notebook
