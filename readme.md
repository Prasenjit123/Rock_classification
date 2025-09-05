Rock Classification using ML & DL Models

This repository contains code and data for a rock classification task using Machine Learning (ML) and Deep Learning (DL) models. The dataset comes from BSE-extracted rock data, and the project compares different approaches for accurate classification.

Repository Contents

rock_classification.py → main source code

README.md → documentation

Dataset → available under Release Assets (see below)

⚙️ Models Implemented

ML models: Logistic Regression, SVM, Random Forest, Gradient Boosting

DL models: Multilayer Perceptron (MLP), Convolutional Neural Network (CNN)

How to Run
Clone the repository

Install requirements
pip install -r requirements.txt

Download the dataset from Releases (BSE_image_extracted_data.xlsx)

Run the script
python rock_classification.py

Dataset

The dataset is not included in the auto-generated Source code (zip/tar.gz) archives.
👉 To download:

Go to the Releases
Select the latest release
Under Assets, download:
BSE_image_extracted_data.xlsx (dataset)

Evaluation

Models were evaluated using accuracy, precision, recall, F1-score, and confusion matrices.
Deep learning models performed better in feature extraction, while ML models offered faster, lightweight alternatives.

Applications

Geological surveys and mining
Automated rock classification
Research and education


