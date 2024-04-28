# Movie Data Analysis and Predictive Modeling

## Project Overview
This project focuses on the analysis, visualization, and prediction of movie-related data. The main objectives are to uncover relationships between various movie features, and to develop machine learning models that can predict the release year and genres of a director's next movie.

## Dataset
The dataset used in this project contains various features related to movies, including:
- Director name, actor names, and their Facebook likes
- Movie budget, gross earnings, and genres
- Plot keywords, IMDb links, and many more

The data is stored in `p1_movie_metadata.csv`.

## Features
Key features engineered and analyzed in this project include:
- Sentiment scores derived from plot keywords
- Profitability and Return on Investment (ROI)
- Popularity scores combining Facebook likes of directors and actors
- Calculated intervals between movie releases

## Installation
To run this project, you will need Python and several libraries which can be installed via pip:
```bash
pip install pandas numpy nltk scikit-learn matplotlib seaborn
```
## Usage
To execute the analysis:

-Clone this repository.
-Ensure you have the required dependencies installed.
-Run the Jupyter notebook.

## Predictive Models
Two main predictive models were developed:

-Genre Prediction Model: Predicts the genres of a movie using a RandomForestClassifier.
-Release Year Prediction Model: Forecasts the interval until the next movie release for a given director using RandomForest and GradientBoosting regressors.

## Visualizations
The plots can be generated inside the notebook and the previous ones can be referred in the report. They include:

-Relationships between various movie features.
-Trends in movie budgets and revenues over the years.
-Popularity of genres based on director's Facebook likes and average gross earnings.

## Results

-The genre prediction model achieved an accuracy of approximately 99.51%.
-Mean Squared Errors (MSE) for the release year prediction were as follows:
 --RandomForest: 0.0633
 --GradientBoosting: 0.0449
 --Ensemble: 0.0470

 ## Conclusions

 The analysis provided insights into the significant impact of director popularity and historical performance on future movie success. Genre trends and financial analytics helped in understanding market dynamics.

 ## Future Work

Further enhancements could include integrating more data such as social media metrics, expanding the feature set, and exploring advanced modeling techniques.




