# MLOps-Project-on-Databricks

This project builds machine learning models to predict whether a person has diabetes or not(classificiation problem). The entire code development process was conducted on Databricks. 

**Dataset**: _diabetes.csv_

**Code Notebooks**:

_diabetes_model_building.ipynb_: this notebook covers EDA, model selection via AutoML(FLAML) and manual fine-tuning, model comparison, and best model deployment on Databricks.

_diabetes_model_inference.ipynb_: this notebook covers model inference on test set and model monitoring report generation before and after feature swapping to compare the differences.

**Video Demo**:
_mlops demo.mp4_: this video is a quick demo to show how to seamlessly run workflows created on Databricks and analyze the inference results of model metrics and monitoring reports logged by mlflow experiments. 


_**Note:** The entire development process for this project was conducted on the Databricks platform. All configurations and Python package dependencies align with Databricks' default settings and runtime environment. If you are running this project outside Databricks, ensure that your Python environment matches the Databricks runtime version used during development._
