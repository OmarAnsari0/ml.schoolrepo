## About the project

This project demonstrates the development and deployment of a predictive model using AWS SageMaker and TensorFlow. The model is a neural network designed for predciting the right species of the penguin. It incorporates end-to-end machine learning pipelines, including data processing, model training, hyperparameter tuning, deployment, and monitoring.

## Components
### Data Processing Pipeline

Data Collection: Aggregates and prepares raw data for analysis.
Feature Engineering: Transforms and selects features for the model.

### Model Pipeline

Model Training: Uses TensorFlow to train a neural network on the processed data.
Hyperparameter Tuning: Utilizes SageMaker's hyperparameter tuning capabilities to optimize model performance.

### Evaluation Pipeline

Model Evaluation: Assesses the model's performance using various metrics to ensure it meets the desired criteria.

### Deployment Pipeline

Model Deployment: The trained model is deployed using AWS EventBridge and Lambda functions, ensuring automated and scalable deployment.

### Monitoring Pipeline

Model Monitoring: Monitors the deployed model's performance and health in real-time, using AWS CloudWatch or similar services.

## Running the code

Before running the project, follow the [Setup instructions](https://program.ml.school/setup.html). After that, you can test the code by running the following command:

```
$ nbdev_test --path program/cohort.ipynb
```

This will run the notebook and make sure everything runs. If you have any problems, it's likely there's a configuration issue in your setup.

## Resources

* [Serving a TensorFlow model from a Flask application](program/serving/flask/README.md): A simple Flask application that serves a multi-class classification TensorFlow model to determine the species of a penguin.
