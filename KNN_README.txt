Simple zoo animals classification using K-Nearest Neighbors algorithm
Developed for Artificial Intelligence & Machine Learning Module

- Uses zoo dataset from UCI Machine Learning Repository.
- KNN classification, aiming to use features bar animal nameto predict 
  the type of animal, such as mammal, amphibian etc.  
  (See UCI link below for more context).
- K-Fold Cross Validation splits data into 10 folds and gets a prediction
  accuracy score for each fold; these are then used to create a mean score.
- K-Fold is run 100 times, so 100 mean accuracy scores are received from
  1000 folds.
- "Grand mean" of all 100 means is printed at the end. For example, a 0.7
  accuracy score means 70% of animal type predictions were correct.
- Arrays for 1 fold are printed, showing predicted vs actual animal types.
- Line graph for 1 fold are printed, showing predicted (blue line) vs 
  actual (red line) animal types.

Will require a Python IDE that integrates-or can integrate-Numpy, matplotlib
and scikit-learn to run (I used Spyder IDE). Save the CSV file in the same
directory as the code file so that the CSV filepath can be left unedited in 
the code.

See more about the Zoo dataset here: http://archive.ics.uci.edu/ml/datasets/zoo