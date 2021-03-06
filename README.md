# Character_Classification

## Project Purpose and Description
The purpose of this project was to classify comic book characters as either good or evil based off features relating to their powerstats and identification. 

## Tools (all using Python and its various libraries)
   - Pandas
   - Numpy
   - Seaborn
   - Matplotlib
   - Scikit Learn

## Data
The Data for this project was scraped from the [Superhero API](https://superheroapi.com/).  Numerical Data from the powerstats category and categoral data such as the characters' biography, appearance, work, and connections were utilized.  

<ins> Features </ins>

Over 700 data points

combat, durability, intelligence, power, speed, strength, overall base, occupation, relatives, alter-egos

<p align="center">
<img src="images/powershist.png" width="700" height="500">
</p>

<img src="images/boxplot.png" width="650" height="650">

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


## Conclusion
After running several models and testing the classification accuracies for the greatest F1 Score,  Random Forest classified the best.  Considering that the sample what relatively small and biased towards good, I would like to classify more characters from different anime based off good and evil incorporating more features and I would also use SMOTE to deal with imbalanced classes.  

![](images/roc.png)

## THERE IS GOOD IN THE WORLD (Fictional World :))

<p align="center">
<img src="images/publisher.png" width="400" height="400">
</p>
