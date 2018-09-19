# Data Scientist Nanodegree
# Write a Data Science Blog Post
## Project: Boston AirBNB Data

### Install

This project requires **Python 3** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [lightgbm](https://lightgbm.readthedocs.io/en/latest/)
- [keras](https://keras.io/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

I recommend you install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project. 

### Motivation for the project

I really wanted to challenge myself on a real-world messy data so I decided to choose this project.Data from Seattle and Boston AirBNB homes can be used to understand how much AirBNB homes are earning in certain time frames and areas.
I compared rates between the two cities,tried to understand if there is anything about the properties that helps predict price. Also, I tried to find negative and positive reviews based on text. 

## File Description
### Dataset 
The dataset can be found at Boston-Airbnb/dat/ and it contains the following:
- [Boston Airbnb Open Data](https://www.kaggle.com/airbnb/boston/home) : As part of the Airbnb Inside initiative, this dataset describes the listing activity of homestays in Boston, MA. 
The following Airbnb activity is included in this Boston dataset: * Listings, including full descriptions and average review score * Reviews, including unique id for each reviewer and detailed comments * Calendar, including listing id and the price and availability for that day
- [Seattle Airbnb Open Data](https://www.kaggle.com/airbnb/seattle/home) : The following Airbnb activity is included in this Seattle dataset: * Listings, including full descriptions and average review score * Reviews, including unique id for each reviewer and detailed comments * Calendar, including listing id and the price and availability for that day

### Jupyter notebook files
It consists of the folowing
- [Predict price.ipynb](https://github.com/ericboss/Boston-Airbnb/blob/master/Predict%20price.ipynb): I used lightgbm (a popular machine learning library used in data science competitions) to predict the price of Boston AirBNB homes based on it's listings data, then I plotted out the most important features for determining the price of a home.
The most relevant features for determining price can be summarized as follows:

![alt text](https://github.com/ericboss/Boston-Airbnb/blob/master/images/predict_price1.png)

 - [Predict_positive_or_negative_ratings_based_on_review.ipynb](https://github.com/ericboss/Boston-Airbnb/blob/master/Predict_positive_or_negative_ratings_based_on_review.ipynb): Here, I tried to predict whether a review is positive or negative based on text. I used deep learning(LSTM) to help me predict that.I got an overall accuracy of about 97%
 - [Price_questions.ipynb](https://github.com/ericboss/Boston-Airbnb/blob/master/Price_questions.ipynb): Here I used basic descriptive statistics to answer questions about the data from Boston and Seattle.

## Acknowledgment
 I really want to thank [udacity](https://www.udacity.com/).I am learning a lot from this program.
