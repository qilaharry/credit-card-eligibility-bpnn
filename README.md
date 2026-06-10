## Project Overview

This project applies a Backpropagation Neural Network (BPNN) to predict credit card eligibility based on applicant demographic and financial information.

The project includes data preprocessing, class imbalance handling, hyperparameter tuning, model training, and model evaluation. Various parameter combinations were tested to determine the configuration that achieved the best classification performance.

## Dataset

The dataset contains demographic and financial attributes of credit card applicants and is used to classify whether an applicant is eligible for credit card approval.

## Results

Several hyperparameters were evaluated during model development, including:

* Test Size
* Hidden Nodes
* Learning Rate
* Batch Size
* Epochs

### Final Model Configuration

* Input Nodes: 18
* Hidden Layer: 1
* Hidden Nodes: 10
* Output Nodes: 1

### Optimal Parameters

* Learning Rate: 0.1
* Epochs: 300
* Batch Size: 10
* Hidden Nodes: 10
* Test Size: 0.1

### Performance

The final model achieved 100% classification accuracy on the test dataset.

Although the model achieved perfect accuracy, further validation using unseen datasets is recommended to ensure the model generalizes well and to reduce the risk of overfitting.

## Skills Demonstrated

* Python
* Google Colab
* Data Preprocessing
* Data Normalization
* Class Imbalance Handling
* Hyperparameter Tuning
* Backpropagation Neural Networks (BPNN)
* Model Evaluation
* Machine Learning
