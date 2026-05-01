![](UTA-DataScience-Logo.png)

# Project Title
Horse Health Classification using Logistic Regression
* **One Sentence Summary** 
This project applies machine learning to predict horse health outcomes using clinical data from a Kaggle dataset.
https://github.com/reelelsadig/DATA3402.Spring.26/blob/main/_Horse%20Health%20Classification%20.ipynb
## Overview
This project focuses on a classification task where the goal is to predict whether a horse is healthy or not based on clinical features. The dataset consists of structured medical data including physiological measurements.The approach taken in this project formulates the problem as a binary classification task using logistic regression. Data preprocessing steps such as cleaning, encoding categorical variables, scaling, and splitting were applied before training the model.The model achieved an accuracy of approximately 72% and an AUC score of about 0.86,  indicating good performance in distinguishing between classes.

## Summary of Workdone
### Data
The dataset used in this project was obtained from Kaggle and consists of structured clinical data for horses. Each row represents an individual horse, and the features include both numerical measurements and categorical attributes related to health conditions. The target variable is binary, indicating whether the horse is healthy or not. The dataset was split into training, validation, and testing subsets to allow for proper evaluation of the model.
#### Preprocessing / Clean up
Several preprocessing steps were performed to prepare the data for modeling. First, irrelevant columns such as identification numbers and hospital-related fields were removed since they do not contribute to prediction. Missing values were handled appropriately, and categorical variables were converted into numerical format using one-hot encoding. Additionally, feature scaling was applied using standardization to ensure all variables are on a similar scale, which improves model performance.
#### Data Visualization
<img width="567" height="435" alt="download" src="https://github.com/user-attachments/assets/a2a23a7c-0200-42dc-88f2-494f897930d5" />
<img width="498" height="455" alt="download" src="https://github.com/user-attachments/assets/1fdad172-bd61-491c-b2c4-1fda2d03243d" />

Basic visualizations were used to explore the dataset, including distributions of features and class balance. These helped identify patterns and potential imbalances in the data.
### Problem Formulation
The problem was formulated as a supervised binary classification task. The input consists of processed clinical features, and the output is a binary label representing the health status of the horse. Logistic regression was chosen as the primary model due to its simplicity, efficiency, and interpretability. The model uses log loss, also known as binary cross-entropy, as the loss function.

### Training
The model was trained using Python in a Jupyter Notebook environment with libraries such as pandas, numpy, and scikit-learn. The training process involved fitting the logistic regression model on the training dataset and evaluating its performance on validation and test sets. Training time was relatively short due to the simplicity of the model. The model converged automatically without requiring complex stopping criteria. Some challenges included handling missing data and ensuring proper feature scaling.
### Performance Comparison

The model was evaluated using accuracy and AUC as the primary performance metrics. Accuracy measures the proportion of correct predictions, while AUC evaluates how well the model distinguishes between classes. The model achieved an accuracy of approximately 72% and an AUC score of about 0.86. These results indicate that the model performs reasonably well for a baseline approach. Visualization tools such as ROC curves were also used to assess model performance.
### Conclusions
The results demonstrate that logistic regression provides a solid baseline for predicting horse health outcomes. The model was able to achieve reasonable accuracy and strong class separation, indicating that the dataset contains meaningful features for prediction.

### Future Work

Future improvements could include experimenting with more advanced machine learning models such as random forests or neural networks. Additional steps like hyperparameter tuning, feature selection, and improved handling of missing data could further enhance model performance.
## How to reproduce results
### Overview of files in repository

The project is organized within a Jupyter Notebook that contains all steps of the workflow, including data preprocessing, model training, and performance evaluation. Each section is clearly labeled to guide users through the process.
ppening.

### Software Setup
To run this project, users need Python and common data science libraries such as pandas, numpy, scikit-learn, and matplotlib. These can be installed using standard package managers like pip.
### Data
The dataset can be downloaded from Kaggle. Once downloaded, it can be loaded into the notebook using pandas for further preprocessing and analysis

### Training

To train the model, users can run all cells in the notebook sequentially. This includes preprocessing the data, encoding features, scaling, and fitting the logistic regression model.
#### Performance Evaluation

Model performance can be evaluated using metrics such as accuracy and AUC, which are calculated within the notebook. Visualization tools such as ROC curves can also be used to assess classification performance.

## Citations

The dataset was obtained from Kaggle, and machine learning tools were implemented using the scikit-learn library.








