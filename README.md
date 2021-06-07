# Airbnb 2018 Seatle analysis

Project carried out with the intention of using a data analysis methodology, called CRISP-DM. <br>
The project can be found in the "notebook" folder

The project aims to answer some questions such as:
Which streets have the homes with the highest average price?<br>
Which streets are best rated? <br>
and What types of properties are most valued?<br>

Also, at the end of the project we will instantiate some machine learning models to try to predict the price based on the characteristics of the residences.

the project structure is formed as follows:

Airbnb Project { <br>
  Data{<br>
    boston.zip<br>
    boston_calendar.csv<br>
    boston_listings.csv<br>
    boston_reviews.csv<br>
    seatle_calendar.csv<br>
    seatle_listings.csv<br>
    seatle_reviews.csv<br>
  }<br>
  
  Notebook{<br>
    Airbnb Project.ipynb<br>
  }<br>
  
README.md

## Data Location

The data used was acquired through the following link: https://www.kaggle.com/airbnb/seattle/data

## Used Libs:

Matplotlib,<br>
Pandas,<br>
Seaborn,<br>
Scikit-Learn<br>
RE (Regular Expression)

## Validation Metrics:
R2 squared,<br>
Mean Squared Error

## Tested machine learning models:¶
LinearRegression,<br>
RidgeCV,<br>
Ridge,<br>
SGDRegressor

## Methodology for data stratification:
RepeatedStratifiedKFold

## External sources used:
Link: https://stackoverflow.com/questions/62619082/check-if-column-in-data-frame-contain-any-word-from-a-list-adding-count-pytho
