# Overview
Assignments 1 - 3 focused on the supervised-learning pipeline, including data cleaning, data preprocessing, 
and training traditional machine learning models.

Assignment 4 explored heuristic optimization by implementing Greedy Algorithm, Simulated Annealing,
and Genetic Algorithm for the Traveling Salesman Problem.

# A1
I performed a complete data-cleaning pipeline on the Alien Pet Health dataset(synthesized dataset).
The work included loading and inspecting the raw data, identifying and handling missing values, standardizing 
categorical attributes, removing non-informative features, analyzing numerical distributions, assessing class balance,
and saving a fully cleaned dataset with correct data types for downstream machine-learning tasks.

# A2
I completed a full machine learning workflow, starting from raw data cleaning to model evaluation
and hyperparameter tuning. I applied normalization and standardization during data preprocessing, 
and trained four models: K-Nearest Neighbors, Decision Trees, Logistic Regression, and Random Forest.
Finally, I performed hyperparameter tuning on these models and achieved an F1-score of 84.7 on the test set.

# A3
I implemented and analyzed a feed-forward neural network. I applied techniques such as early
stopping, L2 regularization, and dropout to improve generalization. I also explored different hyperparameters 
by varying the number of layers, hidden units, and activation functions. My best model achieved an F1 score 
of 0.878 and an ROC-AUC of 0.954, showing a slight improvement over my Random Forest model.

# A4
I implemented and compared two meta heuristic algorithms: Simulated Annealing (SA) and Genetic Algorithms
(GA)to solve the Traveling Salesman Problem (TSP). Both algorithms were tested on two datasets,
and each configuration was run 10 times to evaluate consistency, average performance, and runtime.
