# Iris Flower Classification

## Project Overview

This project implements a Machine Learning model to classify Iris flowers into three species:

* Setosa
* Versicolor
* Virginica

The project uses the classic Iris dataset and Logistic Regression for classification.

## Objective

To build a Machine Learning classification model that predicts the species of an Iris flower based on its physical measurements.

The features used are:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

## Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

## Dataset

The Iris dataset contains **150 flower samples** belonging to three different species:

* Setosa – 50 samples
* Versicolor – 50 samples
* Virginica – 50 samples

The dataset contains four numerical features:

| Feature      | Description               |
| ------------ | ------------------------- |
| Sepal Length | Length of the sepal in cm |
| Sepal Width  | Width of the sepal in cm  |
| Petal Length | Length of the petal in cm |
| Petal Width  | Width of the petal in cm  |

## Project Workflow

1. Load the Iris dataset
2. Explore the dataset
3. Check dataset information and missing values
4. Visualize the data
5. Split the dataset into training and testing sets
6. Train a Logistic Regression model
7. Make predictions
8. Evaluate the model
9. Test the model with a new flower sample

## Data Visualization

The Iris dataset was visualized using a scatter plot based on petal length and petal width.

![Iris Flower Scatter Plot](iris_scatter_plot.png)

## Model Used

### Logistic Regression

Logistic Regression was used as the classification algorithm.

The dataset was divided into:

* **Training data:** 80% – 120 samples
* **Testing data:** 20% – 30 samples

## Model Evaluation

The model was evaluated using the following performance metrics:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

### Accuracy

The Logistic Regression model achieved approximately:

**96.67% accuracy**

### Classification Report

The classification report provides precision, recall, and F1-score for each Iris species.

### Confusion Matrix

The confusion matrix shows the actual and predicted classifications of the test samples.

![Confusion Matrix](confusion_matrix.png)

## Sample Prediction

A new Iris flower was provided to the trained model with the following measurements:

```text
Sepal Length = 5.1
Sepal Width  = 3.5
Petal Length = 1.4
Petal Width  = 0.2
```

### Predicted Species

```text
Setosa
```

## Results

The trained Logistic Regression model successfully classified Iris flowers into their respective species.

The model achieved approximately **96.67% test accuracy**, demonstrating that the selected features are useful for distinguishing the three Iris species.

## Project Files

* `Iris_Flower_Classification_AI_ML.ipynb` – Complete Machine Learning notebook
* `README.md` – Project documentation
* `iris_scatter_plot.png` – Dataset visualization
* `confusion_matrix.png` – Model evaluation visualization

## Conclusion

The Iris Flower Classification project demonstrates the complete workflow of a basic Machine Learning classification problem.

The project covers dataset loading, data exploration, visualization, train-test splitting, model training, prediction, and model evaluation.

Logistic Regression was successfully used to classify Iris flowers into Setosa, Versicolor, and Virginica species.

## Future Improvements

The project can be further improved by:

* Comparing multiple classification algorithms
* Performing hyperparameter tuning
* Adding more visualizations
* Deploying the model as a web application
* Creating an interactive prediction interface

## Author

**Mathavi E**

GitHub: `mathavie622`
