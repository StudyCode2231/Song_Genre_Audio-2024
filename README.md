# Genre Classification Of Songs From Audio Data

## Overview
Our project delves into the realm of music analytics, focusing on classifying songs into genres based on their audio features. Leveraging a dataset sourced from The Echo Nest, we analyze various audio metrics including acousticness, danceability, and energy. Through this endeavor, we showcase the comprehensive process of employing machine learning techniques for song classification, emphasizing the critical role of dataset balancing in enhancing model performance.

## Technologies Used
- **Python 3**: Primary programming language facilitating project development.
- **Pandas**: Essential for efficient data manipulation and cleaning processes.
- **NumPy**: Enables fundamental numerical operations on arrays and matrices.
- **Matplotlib**: Utilized for generating insightful visualizations of data and outcomes.
- **Scikit-learn**: Integral for machine learning model development, offering tools for standardization, Principal Component Analysis (PCA), and model evaluation.
- **Jupyter Notebook**: Facilitates seamless documentation of workflow and analysis, ensuring transparency and reproducibility.

## Key Concepts and Models
- **Exploratory Data Analysis**: In-depth exploration of pairwise relationships among features, augmented by visualization through correlation matrices.
- **Data Preprocessing**: Implementation of standardized procedures for data normalization and partitioning into training and testing sets.
- **Dimensionality Reduction**: Application of PCA to streamline feature space while preserving variance.
- **Model Training and Evaluation**: Employing Decision Trees and Logistic Regression for genre classification, with meticulous comparison of their performance. Techniques such as cross-validation are employed for robust model evaluation.
- **Data Balancing**: Proactive measures taken to address class imbalance, thereby enhancing model fairness and accuracy.

## How It Works
1. **Data Loading and Inspection**: Rigorous examination of raw audio metrics to comprehend their structure and content.
2. **Data Standardization**: Implementation of standardized processes to normalize feature scales, ensuring uniformity across the dataset.
3. **Dimensionality Reduction with PCA**: Application of PCA to reduce dimensionality while retaining crucial variance in the standardized dataset.
4. **Model Training**: Utilization of Decision Tree and Logistic Regression models on the reduced feature set, leveraging scikit-learn's functionalities.
5. **Model Evaluation**: Comprehensive evaluation and comparison of model performance using classification reports and other relevant metrics.
6. **Ensuring Model Reliability**: Implementation of techniques like cross-validation to validate model robustness and reliability.
7. **Analyzing Dataset Balancing Impact**: Examination and visualization of the dataset balancing techniques' impact on model performance.

## Setup/Installation Requirements
- Ensure Python 3 is installed with necessary libraries: Pandas, NumPy, Matplotlib, and Scikit-learn.
- Set up the Jupyter Notebook environment to execute the project notebook.
- Obtain dataset files in CSV and JSON format for seamless integration.

## Acknowledgements
This project is part of a DataCamp course designed to apply practical data science skills in real-world scenarios. Its objective is to demonstrate proficiency in genre classification of songs using machine learning methodologies.

By encapsulating the project's essence and technical intricacies in a succinct manner, this README facilitates easy comprehension for recruiters and interested parties, highlighting the project's significance and potential impact in the field of music analytics.