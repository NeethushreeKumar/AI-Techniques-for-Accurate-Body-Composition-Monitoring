# AI-Techniques-for-Accurate-Body-Composition-Monitoring
This AI project classifies body fat percentage (BFP) to identify health risks like obesity, cardiovascular disease, and diabetes. By applying models like SVM, MLP, CNN, and DBSCAN clustering, it enhances personalized healthcare through accurate BFP classification, supporting proactive health monitoring and tailored interventions.

## Project Overview
This project focuses on using advanced Artificial Intelligence (AI) techniques to accurately classify body fat percentage (BFP) categories. BFP is a critical health indicator that provides more detailed insights than BMI by distinguishing fat and lean body mass, essential for personalized healthcare and fitness planning. This project employs machine learning models to categorize BFP and detect individuals at risk for conditions such as obesity, cardiovascular disease, and diabetes.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results and Evaluation](#results-and-evaluation)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Features
- **BFP Classification**: Categorizes individuals based on body fat levels, from underfat to obese.
- **Multiclass Classification Models**: Implements SVM, MLP, and CNN models to compare classification accuracy.
- **Clustering Analysis**: Uses DBSCAN clustering to explore relationships within data.
- **Data Preprocessing**: Includes missing value handling, outlier removal, feature scaling, and dimensionality reduction.

## Technologies Used
- **Python**: For data analysis and machine learning model implementation
- **Pandas & Numpy**: Data manipulation and processing
- **Matplotlib & Seaborn**: Data visualization
- **Scikit-Learn**: Machine learning algorithms and model evaluation
- **TensorFlow/Keras**: Deep learning models (MLP and CNN)
- **Jupyter Notebook**: Interactive data analysis and model training

## Project Structure
```plaintext
├── data/                         # Dataset files for model training and testing
├── notebooks/                    # Jupyter notebooks for data exploration and model building
├── models/                       # Saved model files and hyperparameter settings
└── visualizations              # Sample charts and model evaluation results                    
