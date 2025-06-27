# Iris Flower Classification

📎 [Open in Google Colab](https://colab.research.google.com/drive/1HemAnPlRF5b7a67IyBCBvnY3nz0LTudI?usp=sharing)

## Project Overview  
Iris Flower Classification is a classic machine learning task that involves classifying iris flowers into three species based on features like sepal length, sepal width, petal length, and petal width. This project demonstrates data preprocessing, exploratory data analysis (EDA), and the application of classification algorithms.

## Dataset  
The dataset contains measurements of iris flowers from three species with the following features:  
- Sepal Length (cm)  
- Sepal Width (cm)  
- Petal Length (cm)  
- Petal Width (cm)  
- Species (target variable)

## Tools & Libraries  
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn (for visualization)  
- Scikit-learn (for modeling and evaluation)

## Project Workflow  
1. Loaded and explored the dataset (checked for missing values, data types, and summary statistics).  
2. Encoded target labels (species) using LabelEncoder.  
3. Visualized feature correlations and distributions using heatmaps and bar plots.  
4. Dropped less relevant features to improve model simplicity.  
5. Split data into training and testing sets.  
6. Trained a Logistic Regression classifier.  
7. Evaluated model performance using accuracy, R² score, and classification report metrics.

## Results  
- Training accuracy: *95.8*  
- R² score on test data: *1.0*  
- Classification report shows precision, recall, and F1-score for each species.
