# House Price Prediction

## Overview

[Youtube-guided](https://youtu.be/Wqmtf9SA_kk?si=J0DOtNAgGoupDGH2) Machine Learning tutorial in Python. The dataset that is being worked on is the [California housing prices dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices?resource=download). The aim was to predict the values from the column "median_house_value" using the values of the other columns with the dataset.


## Usage

Simply access the [jupiter notebook file](https://github.com/toni-the-dude/House-Price-Prediction/blob/main/main.ipynb) attached to this repository to be able to see the code in action.

## Walkthrough

The jupyter notebook is sectioned according to the steps I have taken. My various comments also help explain the code.
<br><br>
The main sections to look for within the code are:
<ol>
  <li>Loading the dataset</li>
  &ensp;Here we make sure the dataset gets loaded in correctly and have our first look at the columns in the dataset.
  <li>Exploring the data</li>
  &ensp;By visualizing the data we figure out which features need adjustment whilst gaining a better understanding of their correlations.
  <li>Preprocessing the data</li>
  &ensp;Using what we learned in the previous step, we modify features to better suit our model.
  <li>Feature engineering</li>
  &ensp;We add extra features.
  <li>Applying the linear regression model</li>
  &ensp;We get to finally observe how close our model can predict the "median_house_value" values using our new features.
  <li>Applying the random forest model</li>
  &ensp;Using a different model, we attempt another, hopefully more accurate predition.
</ol>

## Conclusion

This is my first time seeing Random Tree Forest in action. This, alongside the rehearsal of common Data Science steps and methodologies helped me further memorize and understand the process of building such applications.
