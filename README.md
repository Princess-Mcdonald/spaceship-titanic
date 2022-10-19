<h1> Overview Of Spaceship Titanic </h1>

![spaceship_titanic](https://user-images.githubusercontent.com/83272065/196774164-5d42b715-9b4c-4e5f-b090-fda93d612bcc.png)


##Introduction

Welcome to the year 2912, where your data science skills are needed to solve a cosmic mystery. We've received a transmission from four lightyears away and things aren't looking good.

The Spaceship Titanic was an interstellar passenger liner launched a month ago. With almost 13,000 passengers on board, the vessel set out on its maiden voyage transporting emigrants from our solar system to three newly habitable exoplanets orbiting nearby stars.

While rounding Alpha Centauri en route to its first destination—the torrid 55 Cancri E—the unwary Spaceship Titanic collided with a spacetime anomaly hidden within a dust cloud. Sadly, it met a similar fate as its namesake from 1000 years before. Though the ship stayed intact, almost half of the passengers were transported to an alternate dimension!

you are challenged to predict which passengers were transported by the anomaly using records recovered from the spaceship’s damaged computer system.


## Problem Type: This is a classification problem. 

## Data Source: This is a Kaggle dataset

### A brief description of the data.

PassengerId - A unique Id for each passenger.
              Each Id takes the form gggg_pp where gggg indicates a group the passenger is travelling with and pp is their number within the group.
              People in a group are often family members, but not always.

HomePlanet - The planet the passenger departed from, typically their planet of permanent residence.

CryoSleep - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage.
            Passengers in cryosleep are confined to their cabins.

Cabin - The cabin number where the passenger is staying.

Name - The first and last names of the passenger.

Transported - Whether the passenger was transported to another dimension. This is the target, the column you are trying to predict.

# Modeling 
The Random Forest Classifier gave the best score with our train data and hence was used to predict our test data.
