# Rock Classification using ML & DL Models

This repository contains code and data for a **rock classification task** using **Machine Learning (ML)** and **Deep Learning (DL)** models. The dataset is derived from **BSE-extracted rock image data**, and the project evaluates multiple approaches to achieve accurate classification.

---

## Repository Contents
- `rock_classification.py` → main source code  
- `README.md` → documentation  
- Dataset → available under **Release Assets** (see below)  

---

## Models Implemented
- **Machine Learning models**  
  - Logistic Regression  
  - Support Vector Machine (SVM)  
  - Random Forest  
  - Gradient Boosting  

- **Deep Learning models**  
  - Deep Neural Networks (DNN)  
  - Convolutional Neural Network (CNN)  

---

## How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/rock-classification.git
   cd rock-classification
   ```
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```
3. Download the dataset from [Releases](../../releases) (`BSE_image_extracted_data.xlsx`)  
4. Run the script  
   ```bash
   python rock_classification.py
   ```

---

## Dataset Access
The dataset is **not included** in the auto-generated `Source code (zip/tar.gz)` archives.  

  To download:  
1. Go to the [Releases](../../releases) page  
2. Select the latest release  
3. Under **Assets**, download:  
   - `BSE_image_extracted_data.xlsx` → dataset  

---

## Evaluation
The models were evaluated using:  
- Accuracy  
- Precision, Recall, and F1-score  
- Confusion Matrices  

Deep learning models performed better in **feature extraction**, while traditional ML models provided **faster and lightweight** alternatives.

---

## Applications
- Geological surveys and mining  
- Automated rock classification  
- Research and education  
