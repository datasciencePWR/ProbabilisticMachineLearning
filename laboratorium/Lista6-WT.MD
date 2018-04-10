# Task List 6 - Grupy wtorkowe

### Exercises:

Simple naive bayes classifier



1. Acquire appropriate dataset from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/) (script within notebook/collaboratory, using pandas for manipulation), dataset must be different then Wine, Iris, Glass. In order to have easy task, take dataset with categorical attributes (otherwise you must discretize attributes values or make assumption about normality and estimate pdf's)
2. Create function that calculate each class probability
3. Create function that calculate probabilities for given value in each class for each attribute
4. Using bayes rule create classifier that use computed probiabilities functions
5. Evaluate classifier using train/test split (randomize instances, 80% of data as train, 20% as test)
6. Compute evaluation metrics: accuracy, precission, recall, F1-score
