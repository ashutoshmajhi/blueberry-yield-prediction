# Blueberry-Yield-Prediction

Blueberry Yield Prediction and Exploration
This repository contains a Jupyter notebook (Yield_prediction_and_data_exploration.ipynb) for a machine learning project focused on predicting blueberry yield. The notebook follows a structured approach, from initial data exploration to model development and evaluation.

Approach

The project is structured into eleven main steps, as outlined in the notebook:

Read Data: Loads training, testing, and initial datasets.

Dataset Info and Description: Provides an overview of the dataframes, including data types and non-null counts.

Null Values Check: Confirms that the dataframes do not contain any missing values.

Feature Distribution: Explores the distribution of various features using visualizations like histograms. The target variable, 'yield,' is noted to follow a normal distribution.

Outliers (Box-plots): Visualizes data to identify potential outliers.

EDA (Exploratory Data Analysis): Conducts further analysis to understand the dataset.

Splitting Data: Discusses three possible approaches for splitting the data, with a preference for using the original dataset to create training and testing splits.

Feature Engineering and Transformation: Prepares the data for modeling.

Transformation Pipeline: Establishes a pipeline for data transformation.

Model Development: Trains and validates a model for yield prediction. The best-performing model is identified as a RandomForest Regressor, which achieved an RMSE of 225.43 and an R² score of 0.97.

MLOps Strategy: Outlines a strategy for the machine learning operations of the project.

Dependencies
This project relies on the following Python libraries for data analysis and visualization:

pandas: For data manipulation and reading CSV files.

numpy: For numerical operations.

seaborn and matplotlib.pyplot: For statistical data visualization and plotting.

scipy: Utilized for statistical functions and plotting.

warnings: To manage warnings generated during execution.

subprocess: To check command line outputs.
