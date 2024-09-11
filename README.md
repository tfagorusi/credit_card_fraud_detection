# Credit-Card-Fraud-Detection

This project focuses on a data science approach to  developing a credit card fraud detection machine learning model. In this project, I considered some outlier detection algorithms like KIsolation forest, KNN (from pyOD library) to detect fraud on credit card transactions. In the development stage, MLflow was used for tracking model training experiments. Using the best performing model from my experiments,  I performed batch and online inferences (using FASTAPI app) for model serving. To get this project running on your machine, follow the steps outlined below:
- Run the following prompts on command line interface (CLI):
  
-- `mkdir credit_card_fraud_detection_project` # create a project directory

-- `cd credit_card_fraud_detection_project` # change directory into project directory

-- `git clone https://github.com/tfagorusi/credit_card_fraud_detection.git` # clone repository

-- `python3.10 -m venv venv` # create virtual environment

-- `source venv/bin/activate`  # on Windows: venv\Scripts\activate

-- `python3 -m pip install --upgrade pip setuptools wheel` # update pip

-- `cd credit_card_fraud_detection` # change directory to credit_card_fraud_detection directory

-- `python3 -m pip install -r requirements.txt` # install the dependencies inside the virtual environment

-- `jupyter lab ccfd.ipynb` # open jupyter lab notebook



