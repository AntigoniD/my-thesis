# My-thesis

## Machine Learning Systems in Hotel Reservations using in particular the XGBoost algorithm

### 1. Abstract 
This thesis is entitled "Machine Learning Systems in Hotel Reservations" and analyses the problem of hotel reservation cancellations using machine learning, in particular the XGBoost algorithm.

Online booking platforms for hotels have brought about significant changes in the way customers make reservations and in their behavior. Many bookings are cancelled due to change of plans or various schedules. The question that arises is this: "Can we predict whether a customer will keep their reservation or cancel it?"

The study uses a dataset from Kaggle.com with real data from hotels. For better understanding, exploratory analysis of the data is performed with visualizations and charts using Python. In the data pre-processing stage, new independent variables are added to optimize the analysis.

An XGBoost predictive model is created, which belongs to the machine learning library of gradient-boosted decision trees, known as gradient-boosted decision trees (GBDT). The dataset is divided into training data and test data, and the cross-validation technique helps in better data sharing. Grid Search is also applied to adjust the hyperparameters.

To evaluate the model, the ROC and AUC curves and the SHAP library are used for greater transparency of the factors that influenced the optimization of the model.
Machine learning is a tool, which can be very useful and profitable in the tourism sector.

### 2. Project Structure
This repository contains the following main components:
* notebook/: Contains the Jupyter Notebook (.ipynb) files for data exploration, preprocessing, model training, and evaluation.
* data/: Directory for the raw and processed datasets (Hotel Reservations.csv)
* README.md: This file.

### 3. Technologies Used
* Python 3
* Anaconda: The project was developed and run within an Anaconda environment.
* Jupyter Notebook: Used for interactive development, analysis, and presenting results.
* Key Python Libraries:
  * pandas (for data manipulation and analysis)
  * numpy (for numerical operations)
  * matplotlib (for data visualization)
  * seaborn (for enhanced data visualization)
  * scikit-learn (for machine learning utilities, model evaluation, cross-validation, Grid Search)
  * xgboost (for the predictive model)
  * shap (for model interpretability)
 
### 4. Getting Started
To set up and run this project locally, follow these steps:
* Anaconda (recommended for easy environment management).
* Launch Jupyter Notebook
* A new tab will open in your web browser, showing the Jupyter interface. Create a file to store the main notebook and the data (csv file). Open the main notebook and run the cells sequentially to reproduce the analysis, model training, and evaluation.

### 5. Dataset
The dataset used in this thesis is sourced from Kaggle.com. It contains real-world hotel booking data. ( https://www.kaggle.com/datasets/ahsan81/hotel-reservations-classification-dataset )
    

