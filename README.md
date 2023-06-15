# Flight-Price-Prediction

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Model Creation](#model-creation)
  * [Future scope of project](#future-scope)
  
  ## Demo
  
  ![Screenshot_20230614_032616](https://github.com/HajaraCM/Flight-Price-Prediction/assets/117503246/00e978ae-e346-4616-bf1d-de4be78028ab)
 
  ![Screenshot_20230614_032529](https://github.com/HajaraCM/Flight-Price-Prediction/assets/117503246/9fdf0a6c-8f3a-454f-89fa-c1967afeca19)

## Overview
The Airline Flight Fare Prediction project is to predict airline flight fares across the Indian cities. The dataset for the project is taken from Kaggle, and it is a time-stamped dataset so, while building the model, extensive pre-processing was done on the dataset especially on the date-time columns to finally come up with a ML model which could effectively predict airline fares across various Indian Cities. The dataset had many features which had to pre-processed and transformed into new parameters for a cleaner and simple web application layout to predict the fares. The various independent features in the dataset were:

Airline: The name of the airline.

Date_of_Journey: The date of the journey

Source: The source from which the service begins.

Destination: The destination where the service ends.

Route: The route taken by the flight to reach the destination.

Dep_Time: The time when the journey starts from the source.

Arrival_Time: Time of arrival at the destination.

Duration: Total duration of the flight.

Total_Stops: Total stops between the source and destination.

Additional_Info: Additional information about the flight

Price: The price of the ticket


## Motivation

Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, it will be a different story. We might have often heard travelers saying that flight ticket prices are so unpredictable.Therefore, having some basic idea of the flight fares before planning the trip will surely help many people save money and time.

The main goal is to predict the fares of the flights based on different factors available in the provided dataset.



## Technologies Used


![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) 
<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200><img target="_blank" src="https://github.com/HajaraCM/Crop-Recommendation-System/assets/117503246/30ed18f5-1e65-4f23-854b-2d94ab81c880" width=200> <img target="_blank" src="https://github.com/HajaraCM/Crop-Recommendation-System/assets/117503246/fa4a18b7-6e4b-40a4-b6e9-3491bf2ac0aa" width=170> <img target="_blank" src="https://github.com/HajaraCM/Crop-Recommendation-System/assets/117503246/f7c82eeb-0819-4eb4-ad99-2ee6607b84ee" width=170>


## Model Creation

* Random forest regressor is used to create the flight fare prediction model.
* The model is evaluated using evaluation matrix.


## Future Scope

* Use multiple Algorithms
* Optimize Flask app.py
* Front-End 



