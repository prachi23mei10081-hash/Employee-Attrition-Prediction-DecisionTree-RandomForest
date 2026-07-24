# Employee Attrition Prediction using Decision Tree and Random Forest

## Objective

Build Decision Tree and Random Forest classification models to predict employee attrition and compare their performance.

## Dataset

IBM HR Analytics Employee Attrition & Performance Dataset

Dataset Link:
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

## Libraries Used

* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Methodology

1. Load the dataset.
2. Explore numerical and categorical features.
3. Check for missing values.
4. Remove unnecessary columns.
5. Encode categorical variables.
6. Split the dataset into 80% training and 20% testing.
7. Train a Decision Tree Classifier.
8. Train a Random Forest Classifier with 100 estimators.
9. Evaluate both models using Accuracy, Precision, Recall, and F1-Score.
10. Compare the models using confusion matrices and a Random Forest feature importance plot.

## Results

Both models successfully predicted employee attrition. Random Forest achieved better overall performance than the Decision Tree model.

## Model Comparison

Random Forest provided higher Accuracy, Precision, Recall, and F1-Score than the Decision Tree. It also reduced overfitting by combining multiple decision trees.

## Conclusion

Random Forest proved to be the better model for employee attrition prediction because of its improved accuracy and robustness. Decision Trees are easier to interpret but are more prone to overfitting.

