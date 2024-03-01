# Genre Classification of Songs from Audio Data

## Overview
In this project, we delve into the world of music analytics by classifying songs into genres based on their audio features. The dataset, sourced from The Echo Nest, contains various audio metrics such as acousticness, danceability, energy, and more. The project demonstrates the end-to-end process of using machine learning for song classification, from data loading to model evaluation, emphasizing the importance of balancing datasets for improved model performance.

## Technologies Used
- **Python 3**: The primary programming language used.
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical operations on arrays and matrices.
- **Matplotlib**: For generating visualizations of the data and results.
- **Scikit-learn**: For machine learning model development, including tools for standardization, Principal Component Analysis (PCA), and model evaluation.
- **Jupyter Notebook**: For documenting the workflow and analysis.

## Key Concepts and Models
- **Exploratory Data Analysis**: Investigating pairwise relationships between features and visualizing them using correlation matrices.
- **Data Preprocessing**: Standardizing the data and splitting into training and testing sets.
- **Dimensionality Reduction**: Applying PCA to reduce feature space while retaining variance.
- **Model Training and Evaluation**: Using Decision Trees and Logistic Regression to classify songs into genres, comparing their performance, and utilizing techniques like cross-validation for robust evaluation.
- **Data Balancing**: Addressing class imbalance to improve model fairness and accuracy.

## How It Works
1. The raw audio metrics are loaded and inspected for understanding the structure and content.
2. Data standardization is performed to normalize feature scales.
3. PCA is applied to the standardized data to reduce dimensions.
4. Decision Tree and Logistic Regression models are trained on the reduced feature set.
5. The models are evaluated and compared using classification reports.
6. Techniques such as cross-validation are used to ensure model reliability.
7. The impact of balancing the dataset on model performance is analyzed and visualized.

## Setup/Installation Requirements
* Python 3 with the necessary libraries installed (Pandas, NumPy, Matplotlib, Scikit-learn).
* The Jupyter Notebook environment for running the notebook.
* The dataset files in CSV and JSON format.

## Acknowledgements
This project is part of a DataCamp course, designed to apply practical data science skills in a real-world context. The aim is to showcase the ability to perform genre classification of songs using machine learning techniques.
