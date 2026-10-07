# Iris Flower Species Prediction Model

## Problem Statement
The goal of this project is to predict the species of an iris flower based on its physical measurements.

This is a *classification problem* — the output belongs to one of three categories:
- *0* = Setosa
- *1* = Versicolor
- *2* = Virginica

## Dataset
- *Source:* Iris dataset (Scikit-learn)
- *Features:*
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)
- *Target:* Species (Setosa, Versicolor, Virginica)

## What I Did
- Imported dataset directly from Scikit-learn
- Explored data using describe(), dataset was already clean
- Split data into training and test sets (80/20 split, random_state=1)
- Used enumerate to map target names to their numeric labels
- Trained multiple machine learning models
- Plotted confusion matrix using ConfusionMatrixDisplay
- Created a prediction function to test each flower species accurately on unseen data

## Models Tested & Results

| Model | Parameters | Accuracy |
|---|---|---|
| Random Forest | n_estimators=150, max_depth=5, random_state=42 | *96.66%* |
| Logistic Regression | max_iter=200 | *96.66%* |

## Best Model
Both *Random Forest* and *Logistic Regression* achieved the highest accuracy of *96.66%*, showing strong and consistent performance on this multi-class classification task.

## Key Takeaways
- Both models achieved 96.66% accuracy on unseen data
- The confusion matrix confirmed the model predicted each flower species correctly
- Clean datasets from Scikit-learn allow faster focus on model building and evaluation
- Multi-class classification requires careful evaluation across all three species

## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Author
Jemilah Alao | Data & Business Intelligence Analyst
[LinkedIn](https://www.linkedin.com/in/jemilah-alao-8a684528a)
