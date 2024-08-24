Forest Fire Prediction using Algerian Forest Fire Dataset
Overview
This project aims to predict forest fires in the Algerian region using machine learning algorithms. The dataset used is the Algerian Forest Fire Dataset, which includes meteorological data and fire occurrences. By analyzing and modeling this data, we can predict the likelihood of forest fires and identify key factors contributing to fire incidents.

Dataset
The dataset contains meteorological data for two different regions in Algeria, covering various attributes such as temperature, humidity, wind speed, rain, and more. The dataset is divided into two regions: the Bejaia region and the Sidi Bel-Abbes region. The dataset is preprocessed to remove any inconsistencies and missing values.

Source: Algerian Forest Fire Dataset
Project Structure
The project is organized as follows:

data/: Contains the Algerian Forest Fire Dataset.
notebooks/: Jupyter notebooks used for data exploration, visualization, and modeling.
src/: Python scripts for data preprocessing, feature engineering, and model training.
models/: Saved models for future use.
results/: Visualization outputs and model performance metrics.
README.md: Project documentation.
Methodology
Data Preprocessing:

Handling missing values.
Encoding categorical variables.
Normalizing/standardizing numerical features.
Splitting the data into training and testing sets.
Exploratory Data Analysis (EDA):

Visualizing data distributions and relationships.
Identifying correlations between features and the target variable.
Feature Engineering:

Creating new features based on domain knowledge.
Selecting the most important features for prediction.
Modeling:

Training various machine learning models, such as:
Logistic Regression
Lasso Regression
Ridge regression
Elastic net regression

Model Evaluation:

Comparing models based on performance metrics.
Selecting the best model for prediction.
Generating confusion matrices and ROC curves.
