# Titanic survival

### Goal
Predict if a passenger survived the sinking of the Titanic or not. For each in the test set, predict a 0 or 1 value for the variable.

### Metric

Score is the percentage of passengers you correctly predict. This is known simply as "accuracy”.

### Submission File Format

Submit a csv file with exactly 418 entries plus a header row. Submission will show an error if there is an extra columns (beyond PassengerId and Survived) or rows.

The file should have exactly 2 columns:

    PassengerId (sorted in any order)
    Survived (contains your binary predictions: 1 for survived, 0 for deceased)
```
PassengerId,Survived
 892,0
 893,1
 894,0
 ...
```
