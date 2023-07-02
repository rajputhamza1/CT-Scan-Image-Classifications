# CT-Scan-Image-Classifications

This project focuses on the classification of CT scans to identify patients infected by SARS-CoV-2 (COVID-19). The dataset used for this project contains 1252 CT scans that are positive for COVID-19 and 1230 CT scans for patients non-infected by SARS-CoV-2, resulting in a total of 2482 CT scans. These scans were collected from real patients in hospitals from Sao Paulo, Brazil.

The aim of this dataset is to encourage the research and development of artificial intelligent methods which are able to identify if a person is infected by SARS-CoV-2 through the analysis of his/her CT scans.

# Dataset
The dataset for this project can be accessed from the following link: [CT Scan Dataset](https://drive.google.com/drive/folders/1WOeodRmv1Mw5Cswuip3nUIi6ViQWKpo_?usp=sharing)

The dataset contains two categories of CT scans:

COVID-19 Positive: This category includes 1252 CT scans of patients who are positive for SARS-CoV-2 infection (COVID-19).

Non-Infected: This category includes 1230 CT scans of patients who are not infected by SARS-CoV-2.

Please download the dataset from the provided link and ensure that the CT scan images are organized in the appropriate folder structure for the code to work correctly.

# Code Evaluation
The code has been evaluated using the provided CT scan dataset. The evaluation results are as follows:

**Accuracy**: 91.00%

**Precision**: 89.33%

**Recall**: 93.00%

**F1-Score**: 91.13%

These metrics indicate the performance of the classification model in identifying COVID-19 infection based on CT scan images. The accuracy represents the overall correctness of the predictions, while precision measures the proportion of true positive predictions out of all positive predictions. Recall measures the proportion of true positive predictions out of all actual positive samples. The F1-Score is a balanced measure of precision and recall.

The high accuracy, precision, recall, and F1-Score obtained from the evaluation indicate that the CT scan image classification model performs well in identifying patients infected by SARS-CoV-2 using CT scan images.

# Repository Structure
The repository contains the following files:

**CT Scan Image Classification.ipynb**: Jupyter Notebook containing the code for CT scan image classification.

**README.md**: This readme file.

# Getting Started
To run the code and reproduce the results:

Clone the repository: git clone <https://github.com/rajputhamza1/CT-Scan-Image-Classifications>

Ensure you have the necessary dependencies installed. 

You can install them using the provided '**requirements.txt'** file: **pip install -r requirements.txt**

Download the CT scan dataset from the provided link.

Extract the downloaded dataset and place the COVID-19 positive and non-infected CT scan images in the data directory.

Open the CT_scan_classification.ipynb notebook in Jupyter Notebook or any compatible environment.

Follow the instructions in the notebook to execute the code cells and train the CT scan classification model.

Evaluate the performance of the trained model using the provided evaluation metrics.

# Further Steps
This project can serve as a starting point for further research and development in the field of CT scan image classification for COVID-19 detection. Possible next steps include:

Exploring alternative model architectures and algorithms for improved performance.

Conducting more extensive hyperparameter tuning to optimize the model's performance.

Considering additional preprocessing and feature extraction techniques.

Evaluating the model on external datasets to assess its generalization capabilities.

Implementing a user-friendly interface or deploying the model as a web application for real-world usage.

# Contributing
Contributions to the project are welcome. If you have any suggestions, improvements, or bug fixes, please submit a pull request or open an issue.





