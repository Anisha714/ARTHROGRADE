# 🦴 ARTHROGRADE - Arthritis Grade Detection using Machine Learning
 📊 Dataset

The dataset used for this project can be downloaded from the following link:
📥 [https://www.kaggle.com/datasets/hafiznouman786/annotated-dataset-for-knee-arthritis-detection]
 
This repository explores various machine learning and deep learning techniques for the detection and classification of minor knee arthritis. It is designed for educational and research purposes, offering implementations using Convolutional Neural Networks (CNN), Explainable AI (XAI) techniques, and traditional machine learning models.

Overview Knee arthritis is a common condition affecting many individuals, and early detection can lead to better management and treatment. This project demonstrates several approaches for diagnosing knee arthritis using imaging data:

CNN Models: Deep learning models for automated feature extraction and classification.

Explainable AI (XAI): Integrating XAI with CNN to provide insights into model predictions.

Traditional Machine Learning: Utilizing SVM, RandomForest, and XGBoost for comparative analysis.

Repository Structure The repository is organized into distinct folders, each dedicated to a specific model or technique:

. ├── knee-CNN/

CNN-based model implementation for image classification
├── knee-XAI-app-py-cnn/

XAI integrated with CNN for model interpretability
├── knee-svm-randomforest/

Traditional ML models using SVM and RandomForest
└── knee-xgboost-randomforest/

Implementation using XGBoost and RandomForest
Each folder contains Jupyter Notebooks and Python scripts that include data preprocessing, model training, evaluation, and visualization.

Installation To get started with the project, follow these steps:

Clone the Repository:

git clone (https://github.com/Anisha714/ARTHROGRADE.git)

Navigate to the Repository:

cd Minor-knee-athritis

Set Up a Virtual Environment (Recommended):

python -m venv venv source venv/bin/activate # On Windows use: venv\Scripts\activate

Install Dependencies:

pip install -r requirements.txt 
Note: Ensure you have Python 3.x installed. Most of the project is developed using Jupyter Notebook for an interactive analysis experience.

Usage CNN Model: Open and run the notebooks located in the knee-CNN directory to train and test the CNN model.

Explainable AI (XAI) with CNN: Use the notebooks in the knee-XAI-app-py-cnn folder to explore model interpretability techniques.

SVM & RandomForest: Refer to the knee-svm-randomforest folder for scripts and notebooks that implement these traditional machine learning models.

XGBoost & RandomForest: The knee-xgboost-randomforest folder contains implementations that utilize XGBoost for comparative studies.

Each section includes detailed instructions within the respective notebooks to guide you through data loading, model training, and evaluation.

Data The project uses imaging data to classify knee arthritis. If you plan to use your own dataset, make sure to format it similarly to the provided examples and update the data loading sections in the notebooks accordingly. If applicable, cite the original source of the dataset as required.

Results and Evaluation For each model, the project provides:-

Performance Metrics: Accuracy, precision, recall, and F1-score.
Visualizations: Confusion matrices, ROC curves, and XAI visual outputs to explain model decisions.
Comparative Analysis: Insights into the performance differences between deep learning and traditional machine learning approaches.

🏥 Use Cases
Early diagnosis of arthritis severity
Assisting radiologists in interpreting results
Reducing subjectivity in arthritis grading
