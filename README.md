# 🐶🐱 Dogs vs Cats Image Classification using XGBoost

This project implements an **image classification system** to distinguish between **dogs and cats** using the popular **Kaggle Dogs vs Cats dataset**.  
Instead of deep learning (CNNs), this project demonstrates how **XGBoost**, a powerful gradient boosting algorithm, can be applied to image-based classification using extracted features.

---

## 📌 Two-Line Description

The Dogs vs Cats dataset from Kaggle contains labeled images of dogs and cats for a binary classification task.  
This project uses feature extraction techniques and trains an **XGBoost classifier** to accurately predict whether an image belongs to a dog or a cat.

---

## 📋 Dataset Overview

- **Source:** Kaggle – Dogs vs Cats Competition  
- **Link:** https://www.kaggle.com/c/dogs-vs-cats/data  

### Dataset Contents
- `train.zip` – Labeled images of cats and dogs  
- `test1.zip` – Unlabeled images for prediction  
- Each image belongs to one of two classes: **Dog** or **Cat**

> ⚠️ Due to GitHub size limitations, large datasets are managed using **Git LFS**.

---

## 🧠 Approach & Methodology

This project follows a traditional machine learning workflow for image classification:

1. **Image Preprocessing**
   - Resize images
   - Normalize pixel values
2. **Feature Extraction**
   - Convert images into numerical feature vectors
3. **Model Training**
   - Train an **XGBoost classifier** on extracted features
4. **Prediction**
   - Predict labels for unseen images
5. **Submission**
   - Generate Kaggle-compatible submission file

---

## 📂 Repository Structure

```text
SCT_WD_3/
│
├── Image_Classification_(Cats_vs_Dogs).ipynb   # Data preprocessing, feature extraction & model training
├── README.md                                  # Project documentation
├── sampleSubmission.csv                       # Kaggle submission format
│
├── train.zip                                  # Training images (Git LFS)
├── test1.zip                                  # Test images (Git LFS)
├── .gitattributes                             # Git LFS configuration

```

## **⚙️ Technologies Used**
Programming Language: Python
Environment: Jupyter Notebook
Libraries:numpy,pandas,opencv / PIL,scikit-learn,xgboost and matplotlib

## 🚀 **How to Run the Project**

**1️⃣ Clone the Repository**:
git clone https://github.com/ashwin8332/SCT_WD_3.git
cd SCT_WD_3

**2️⃣ Install Required Libraries**:
pip install numpy pandas scikit-learn xgboost opencv-python matplotlib

**3️⃣ Run the Notebook**:
Open Jupyter Notebook and execute:
Image_Classification_(Cats_vs_Dogs).ipynb

## **📈 Model Output**
The trained XGBoost model predicts whether an image is a dog or a cat
Predictions can be exported in Kaggle submission format
Performance depends on feature quality and preprocessing

## **📝 Notes**
This project demonstrates machine learning on images without deep learning
Feature extraction quality plays a critical role in model accuracy
Can be extended using:
CNN feature extractors
Transfer learning
Hyperparameter tuning

## **📌 Future Improvements**
Use pretrained CNNs for feature extraction
Apply hyperparameter tuning to XGBoost
Compare results with deep learning models
Add cross-validation and performance metrics

## **🙌 Acknowledgements**
Kaggle for providing the Dogs vs Cats dataset
Open-source Python and ML community
If you find this project useful, feel free to star the repository!
