# Housing-Price-Project
# California Housing Price Prediction Project

Overview

This project aims to build a machine learning model to predict median housing prices in different districts of California using the California housing dataset from the StatLib repository (1990). The dataset includes various metrics such as population, median income, and median housing price for each district in California.

The project follows a structured approach, covering data acquisition, exploration, preprocessing, model selection, training, evaluation, and fine-tuning.

Project Workflow

Data Acquisition: Obtaining and downloading the California housing dataset. Used the 'housing.csv' data

Data Preparation:

Seperating the dataset into a training set and a test set.
Exploring and visualizing the data to gain insights, including visualizing geographical data, looking for correlations, and experimenting with attribute combinations.
Preparing the data for machine learning algorithms, which includes cleaning the data, handling text and categorical attributes, feature scaling and transformation, and implementing custom transformers and transformation pipelines.


Model Selection and Training:

Selecting appropriate machine learning models.
Training and evaluating the models on the training set.
Implementing better evaluation techniques using cross-validation.


Model Fine-Tuning:

Fine-tuning the models using techniques such as grid search, randomized search, and ensemble methods.
Analyzing the best models and their errors.
Evaluating the system on the test set to ensure generalization.


Deployment and Maintenance:

Launching the system for prediction.
Maintaining the system and monitoring its performance over time.

Libraries Used

The project utilizes various Python libraries for data analysis, machine learning, and visualization. The relevant libraries include:

NumPy: For numerical computing and array operations.

Pandas: For data manipulation and analysis.

Matplotlib: For data visualization and plotting.

Scikit-learn: For machine learning algorithms, model selection, and evaluation.

SciPy: For scientific computing and statistical functions.
