# logistic-regression

## Dataset

The dataset used in this project contains various chemical properties of wines, such as:

Alcohol

Color Intensity

Total phenols

These features were scaled by standardization. The data is loaded and processed using Pandas, and NumPy is employed for numerical operations.

## Methodology

1. Data Preprocessing

Standardization of features.

Conversion of labels to one-hot encoded format for multi-class classification.

Splitting the data into training, validation, and test sets.

3. Evaluation

Computation of accuracy for the training, and test sets.

Construction of a confusion matrix to analyze classification performance and identify misclassified samples.

Confusion Matrix Visualization:

A confusion matrix is plotted to understand the performance of the classifier across different wine classes.

## Results

Accuracy

The model achieved a notable accuracy for correctly classifying wine samples

## Visualizations

Error History Plot
Shows the reduction in cross-entropy error over iterations for each class.

## Additional code file

This file evaluates the model for different learning rates and provides the optimized one

## Future Enhancements

Integration of more advanced models such as decision trees or neural networks.

Feature selection or dimensionality reduction for improved performance.

Validation using larger and more diverse datasets.

## Conclusion

This project successfully demonstrates a workflow for training and evaluating a multi-class classification model on wine data using logistic regression and gradient descent. While the model performs well, further improvements can be explored to enhance its robustness and generalization capabilities.
