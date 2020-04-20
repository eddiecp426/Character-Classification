# Character_Classification

## Project Purpose and Description
The purpose of this project was to classify comic book characters as either good or evil based off features relating to their powerstats and identification. 

## Data
The Data for this project was scraped from the [Superhero API](https://superheroapi.com/).  Numerical Data from the powerstats category and categoral data such as the characters' biography, appearance, work, and connections were utilized.  


<p align="center">
<img src="images/powershist.png" width="700" height="500">
</p>

<img src="images/boxplot.png" width="650" height="650">

<ins> Features </ins>

Over 700 data points

combat, durability, intelligence, power, speed, strength, overall base, occupation, relatives, alter-egos

## Outcome

Initial Outcome <br/>
Good: 69% <br/>
Evil: 31%

<p align="center">
  <img src="images/outcome.png" width="500">
</p>


##  Top Models Evaluation Accuracy Score 

Random Forest - 0.7484 <br />
SVM - 0.7161 <br />
GradientBoost - 0.7032 <br />

## Confusion Matrix Metrics for Random Forest

<img src="images/rfconmatrix.png" width="700" height="500">

Classification Accuracy - 0.7484 <br />
Classification Error - 0.2516 <br />
Recall - 0.9009 <br />
Precision - 0.7273 <br />
F1 Score - 0.8189

## Feature Importance for Random Forest
<p align="center">
<img src="images/featimp.png" width="800" height="700">
</p>

## ROC Curve

![](images/roc.png)

## Conclusion
After running several models and testing for the greatest F1 Score,  Adaboost classified the best.  Considering that the sample what relatively small and biased towards good, I would like to classify characters based off good and evil incorporating more features and also used SMOTE to deal with imbalanced classes.  







