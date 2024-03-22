# AI_models
Please note that all code was written within Google Colaboratory. Copying this code directly into 
Jupyter notebooks will result in errors due to the presence of google-specific code.

This is a repository which demonstrates various A.I. Models and exploratory data analysis (EDA) 
techniques from various Python packages/libraries.

To run this code, the following packages will need to be installed in your Python environment. You can 
install the packages from your console/terminal with the 'pip' format:
> pip install seaborn
>
## Packages:
* numpy
* pandas
* matplotlib
* seaborn

## Projects:

1. FoodHub_EDA
   This is an EDA notebook that explores the 'foodhub_order.csv' dataset.

2. AllLifeBank_ML_DecisionTree
   This notebook uses the 'Loan_Modelling.csv' dataset to create 'Decision Tree' machine learning models.
   Steps to complete feature-engineering tasks are included. The following models are included:
   - limiting the 'max_depth' of the tree
   - performing a GridSearchCV
   - Cost-Complexity (pre-pruning)
   - Post-pruning

3. TheraBank_ML_Advanced
   This notebook uses the 'BankChurners.csv' dataset to create advanced machine learning models. These models
   include the use of oversampled and undersampled data approaches for the following models:
   - AdaBoost
   - GradientBoost
   - XGBoost
   - Random Forest
   - Bagging

5. Bank_NeuralNetwork
   This notebook explores a Neural Network model and uses the 'Bank_NN.csv' data set with the following model
   configrations:
   - Adam Optimizer
   - with Dropout
   - with Hyperparameter Tuning
   - with Balanced Data

6. PlantClassification_ComputerVision
   This notebook uses two datasets: 'images.npy' (images) and 'Labels.csv' (labels) to create a computer vision
   model that can recognize and classify various plant seedlings.

7. Generative-IT_LLM_NLP
   This ticket uses a 'hugging face' repository llama-based LLM to classify incoming IT support ticket requests
   and formulate a response via prompts. The data is from 'support_ticket_text_data_mid_term.csv'. Note that tha
   prompts I used will not necessarily generate the the exact same response for you (if you run the code).
   

   
    
