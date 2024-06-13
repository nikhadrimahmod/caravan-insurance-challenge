The repo is a solution to the Caravan Insurance Challenge on Kaggle (https://www.kaggle.com/datasets/uciml/caravan-insurance-challenge).
The challenge originated from the The CoIL Challenge 2000 (https://liacs.leidenuniv.nl/~puttenpwhvander/library/cc2000/).

The goal here is to optimize the caravan insurance sales by predicting a number of customers who are likely to purchase the policy.

The label is binary, 0 (not purchased) and 1 (purchased). We will be using binary classifiers such as probabilistic models e.g. Logistic Regression and Naive Bayes.
On top of that, tree models like Random Forest, Decision Tree are also been used. KNN is also used.

Summary:

1. We want to predict who wants to buy a caravan insurance policy.
2. It is binary classification problem.
3. Data is noisy, skewed, and imbalanced.
4. Feature engineering was done to create higher correlated features.
5. Precision, recall, and precision-recall curve were used as the evaluation metrics.
6. Probabilistic models performed the best, followed by tree models, and KNN.
7. Logistic Regression and Naive Bayes were really competitive.
8. Naive Bayes was chosen because it can be more precise at a lower recall.
   
