## Projects

### Decision Tree - Machine learning
I trained and compared two decision trees to predict diabetes using the Glucose and DiabetesPedigreeFunction variables:

Shallow tree (max_depth=2): about 76% accuracy on the training data and 69% on the test data.
Deeper tree (max_depth=10): about 93% accuracy on the training data, but only 68% on the test data.
These results illustrate the phenomenon of overfitting: a more complex model (depth 10) can better “memorize” the training data without improving its ability to predict new data. The simpler model (depth 2) generalizes slightly better, even though its training accuracy is more modest.

Source code :  
[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40'>](https://github.com/kabirim/machineLearningProjects)

![Octocat](./images/result_decision_tree_clustred.jpg)

### Comparative Analysis of Gini Impurity vs. Entropy in a Random Forest Classifier, With and Without PCA

This project focuses on building a Random Forest classifier using two different impurity measures—Gini and Entropy—and comparing their performance on the same dataset. Additionally, it examines how applying Principal Component Analysis (PCA) as a dimensionality-reduction technique affects classification results. By measuring and comparing key metrics, under both criteria and with or without PCA, the project highlights the trade-offs between different impurity measures and the impact of dimensionality reduction. This work also includes data preprocessing, exploratory data analysis, and hyperparameter tuning, providing a comprehensive overview of the end-to-end machine learning workflow.

![Octocat](./images/output_CM_RF_Gini.png) ![Octocat](./images/output_CM_RF_Entropy.png) 
![Octocat](./images/outputCM_RF_PCA_Gini.png) ![Octocat](./images/output_CM_RF_PCA_Entropy.png)

Source code :  
[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40'>](https://github.com/kabirim/machineLearningProjects)

[Back](./)
