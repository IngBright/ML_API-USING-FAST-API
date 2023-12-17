# ML_API-USING-FAST-API
## Introduction
This project explores the application of machine learning classification models to predict sepsis.

## Business Understanding
In shaping our project's trajectory, we center our attention on a critical healthcare challenge: predicting sepsis onset based on patient data.

## Data Understanding
### Loading Datasets and Exploratory Data Analysis (EDA)
Initiating the project with loading datasets and conducting exploratory data analysis (EDA) to gain insights:
- What features are available in the dataset?
- How should missing values be handled?
- What is the distribution of sepsis cases in the dataset?

## Data Preparation
### Data Splitting and Balancing Classes
Addressing class imbalance by splitting data into training and testing sets and employing techniques such as oversampling or undersampling.
### Creating a Preprocessing Pipeline
Developing a preprocessing pipeline to streamline tasks like imputing missing values, scaling features, and encoding categorical variables.

## Model Training and Evaluation
### Selecting and Training Models
Experimenting with classification models (Random Forest, Logistic Regression, Gradient Boosting) to identify well-performing models for sepsis prediction.
### Model Evaluation
Utilizing metrics like precision, recall, and F1 score with a focus on sensitivity for effective sepsis case capture.
### Hyperparameter Tuning
Achieving optimal model performance through hyperparameter tuning using techniques like grid search or random search.
### Model Persistence
Persisting selected models for easy deployment, eliminating the need for retraining.

## FastAPI and Dockerization
### Building a FastAPI
FastAPI serves as the foundation for our API, designed to take patient data as input and return the predicted likelihood of sepsis onset.

### Docker Containerization
Encapsulating the solution within a Docker container to ensure consistency and eliminate dependency issues across different environments.

## Conclusion
By combining machine learning, FastAPI, and Docker, we create a robust solution for predicting sepsis onset."Predicting Sepsis Onset using FastAPI: A Dockerized Machine Learning Approach," underscores the intersection of technology and healthcare for impactful predictive analytics.
