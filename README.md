# Paris_AirBnB_Good_Deal_Prediction
Good Deal Prediction Modelling based on AirBnB listings in Paris

This is my personal project in which I explore AirBnB listings in Paris, investigate what factors help to get place rented, 
define and identify listings that represent a 'good deal' to travelers, build and train models.

DATA was obtained from open source website http://insideairbnb.com/get-the-data.html that scraps AirBnB listings periodically. It is too 
large to be uploaded to github, but similar formats are available on above site.

NAVIGATION:

DATA CLEANING: 
This folder contains 3 jupyter notebook files with cleaning procedures addressing data transformation and missing values. Detailed steps
can be found in Data Cleaning and Wrangling for AirBnB.pdf from the same folder.

EXPLORATORY DATA ANALYSIS:
The jupyter notebook file in this folder tells the story about AirBnB listings in Paris through graphical representations and 
finding dependencies.

INFERENCIAL STATISTICS:
This folder contains python code for hypothesis testing on whether the prices of different room type (entire apartment, private or 
shared room) listings have the same price.

MACHINE LEARNING:
1. Sentiment analysis - file with python code to calculate average sentiment score for each listing by first translating non-English 
reviews and then calculating sentiment score for each review.
2. Machine learning - final data preparation for building models, addressing ways to deal with imbalanced data, building and training 
models to predict a 'good deal' listing, optimizing model performance.

DATA:
Final data files for predictors and target variable used in machine learning stage.
