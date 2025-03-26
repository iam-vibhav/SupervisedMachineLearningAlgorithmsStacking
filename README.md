# SupervisedMachineLearningAlgorithmsStacking
This repository contains the implementation of a stacked machine learning model for classifying breast cancer cases based on the Wisconsin Diagnostic Breast Cancer Dataset. It leverages multiple base models and a meta-model to achieve improved accuracy and generalizability.




## Project Structure



### Raw Data

###### Directory: `1-RawData/`
`1-RawData/wdbc.data`: Original dataset.<br>
`1-RawData/breast_cancer_modified.csv`: Modified version for preprocessing.<br>
`1-RawData/breast_cancer_selected.csv`: Feature-selected dataset.


### Data Preprocessing

###### Directory: `2-DataPreprocessing/`

Contains notebooks for:
* Handling missing values.
* Scaling features.
* Splitting the dataset into training and testing sets.


### Base Model Training

###### Directory: `3-BaseModelTraining/`

Base models trained include:

`Logistic Regression`
`Decision Tree`
`Random Forest`
`Support Vector Machine`
`K Nearest Neighbours`
`Gradient Boosting`
`AdaBoost`

Each model has a dedicated notebook for training and evaluation.


### Trained Models

###### Directory: `4-TrainedModels/`

        Contains serialized models saved as .pkl files for reuse.


### Stacked Model

###### Directory: `5-BaseModelStacking/`

        Implements the stacked model using outputs from base models.

        Includes a meta-model for final predictions.



        

## Features and Models

    Base Models: Logistic Regression, Decision Tree, Random Forest, SVM, KNN, Gradient Boosting, and AdaBoost.

    Stacking Strategy: Combines predictions of base models using a meta-model (Logistic Regression) to improve performance.

    Feature Engineering: Preprocessing steps include feature scaling, selection, and handling missing values.
