# MOVIE RATING PREDICTION

## Introduction
This project aims to predict the rating of movies based on various features such as the year of release, number of votes, duration, genre, director, and actors. Predicting movie ratings can provide valuable insights for movie enthusiasts, filmmakers, and production companies. The prediction is made using machine learning techniques, specifically a Linear Regression model, trained on a dataset of movies.

## Libraries Used
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib and Seaborn**: For data visualization.
- **Plotly**: For interactive visualizations.
- **Scikit-learn**: For machine learning tasks such as model selection and evaluation.

## Dataset
The dataset used in this project contains information about movies, sourced from various sources such as IMDb or other movie databases. The dataset includes the following columns:
- **Name**: The title of the movie.
- **Year**: The year of release.
- **Duration**: The duration of the movie in minutes.
- **Genre**: The genre(s) of the movie.
- **Rating**: The IMDb rating of the movie.
- **Votes**: The number of votes the movie has received.
- **Director**: The director(s) of the movie.
- **Actor 1, Actor 2, Actor 3**: The main actors in the movie.

## Data Preprocessing
- **Handling Missing Values**: Rows with missing essential information such as name, year, duration, rating, votes, director, and actors are dropped.
- **Data Cleaning**: Textual parts are extracted from the 'Name' column, brackets are removed from the 'Year' column, and non-numeric parts are removed from the 'Duration' column.
- **Feature Engineering**: Genre is split and only unique genres are kept. Votes are converted to numeric and commas are removed.
- **Data Transformation**: Numerical features are scaled or encoded as necessary.

## Exploratory Data Analysis (EDA)
- Insights are gained on the distribution of ratings, genres, directors, and actors.
- Visualizations such as histograms, bar plots, and stacked bar plots are used to explore the data and understand relationships between variables.

## Model Building
- **Feature Selection**: Features such as year, votes, duration, genre mean rating, director encoded, and actor encoded are selected for model training.
- **Model Selection**: A Linear Regression model is chosen for its simplicity and interpretability.
- **Model Training**: The model is trained on the dataset using the selected features.
- **Model Evaluation**: Performance metrics such as mean squared error, mean absolute error, and R2 score are used to evaluate the model's performance.

## Visualization

From the first graph plotted for Most Number of Ratings Year-wise, we can see that maximum number of votes for casted in around 2010 for My Name Is Khan.
<br />

In the second graph depicting the distribution of genres based on the year of release, it's evident that there has been a consistent trend over the years where a larger proportion of movies belong to the Drama genre. This indicates that Drama-based movies have been consistently produced throughout the years.

Upon closer inspection of the third graph illustrating the distribution of highly rated movies by genre over the years, it becomes apparent that Drama is indeed one of the most prevalent genres among highly rated movies. This suggests that Drama-based movies tend to receive higher ratings from viewers compared to other genres. Therefore, the popularity of Drama genre movies, as depicted in the second graph, aligns with the high ratings they receive, as observed in the third graph. This correlation implies that audiences generally enjoy Drama genre movies and are more likely to rate them highly.
## Results
- The trained Linear Regression model achieves high accuracy in predicting movie ratings.
- Performance metrics indicate low mean squared error and mean absolute error, and high R2 score, suggesting that the model provides reliable estimates of movie ratings.

## Prediction Example
- An example is provided to demonstrate how to use the trained model to predict the rating of a new movie.
- Input data containing features such as year, votes, duration, genre mean rating, director encoded, and actor encoded is used for prediction.
- The predicted rating is displayed based on the input data.

## Conclusion
- The code successfully predicts movie ratings based on various features, providing valuable insights for movie enthusiasts, filmmakers, and production companies.
- Further improvements and enhancements could be made by incorporating additional features, experimenting with different machine learning algorithms, or refining the preprocessing steps.

## Usage
1. Install the required libraries mentioned in the "Libraries Used" section.
2. Download the dataset or use your own movie dataset.
3. Run the provided code in a Python environment.
4. Follow the instructions in the code comments to preprocess the data, build the model, and make predictions.

