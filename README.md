# Character_Classification

The purpose of this project was to classify comic book characters as either good or evil based off features relating to their powerstats and identification. 

## Data
The Data for this project was scraped from the Superhero API.  Numerical Data from the powerstats category and categoral data such as the characters' biography, appearance, work, and connections were utilized.  

A majority of the categorical features was made binary (1 for YES and 0 for NO).

## Feature Engineering
Before engineering, the features used were the powerstats, base, occupation, aliases, and relatives and the character's publisher.  

## Predictor

Initial Outcome <br />
Good: 69% <br />
Evil: 31%

##  Top Models Evaluation Accuracy Score 

AdaBoost - 0.7307692307692307 <br />
Stochastic Gradient Descent - 0.717948717948718 <br />
Gradient Boost - 0.717948717948718 <br />

## Confusion Matrix Metrics for Adaboost

Classification Accuracy - 0.7307692307692307 <br />
Classification Error - 0.2692307692307693 <br />
Recall - 0.8148148148148148 <br />
Precision - 0.6875 <br />
F1 Score - 0.8396946564885496

## Conclusion
After running several models and testing for the greatest F1 Score,  Adaboost classified the best.  Considering that the sample what relatively small and biased towards good, I would like to classify characters based off good and evil incorporating more features and also used SMOTE to deal with imbalanced classes.  


