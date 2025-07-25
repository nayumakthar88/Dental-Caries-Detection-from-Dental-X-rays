# 🦷 Dental Caries Detection from Dental X-rays

This project focuses on the detection of **dental caries (tooth decay)** using dental X-ray images and statistical health data. It combines traditional machine learning methods, deep learning models, and image processing techniques to accurately identify and analyze dental health conditions.

## 📌 Project Overview

Dental caries is one of the most common chronic diseases worldwide, affecting both children and adults. Early detection through diagnostic imaging, such as X-rays, can significantly improve treatment outcomes. This project explores:
- Analysis of dental data from CSV files.
- Image preprocessing and edge detection on dental X-rays.
- Training ML and DL models to classify caries presence.
- Data visualization and performance evaluation.

## 🧪 Technologies & Tools Used

- **Languages**: Python
- **Libraries**:
  - `pandas`, `numpy` – Data preprocessing
  - `matplotlib`, `seaborn` – Data visualization
  - `scikit-learn`, `RandomForest`, `SVM`, `YOLO` – Machine Learning
  - `OpenCV` – Image processing (Canny edge detection)
  - `Labelme` – Image annotation
- **Techniques**:
  - Data cleaning and feature engineering
  - Confusion matrix, precision, recall, F1-score
  - Model training/testing with split sets

## 📊 Dataset

- **Source**: Dental health CSV dataset with patient-wise information including age groups, service usage, and utilization rates.
- **Images**: Panoramic dental X-rays with categories like caries, infection, fractured, and healthy teeth.
- **Data Processing**: Null handling, numerical conversion, annotation via Labelme.

## 📷 Image Processing

X-ray images were processed using:
- **Grayscale conversion**
- **Gaussian blur**
- **Canny edge detection**

This improves the visibility of boundaries and caries indicators.

## 📈 Performance Metrics

Models were evaluated using:
- **Precision, Recall, F1 Score**
- **Confusion Matrix**
- **Mean Squared Error**
- **R² Score**

## 🧠 Machine Learning Models

- **Random Forest Regressor**: Predicted utilization percentages.
- **Support Vector Classifier**: Used for binary classification of caries.
- **Deep Learning CNNs (YOLO)**: Used for object detection and localization of caries in panoramic images.

## 📍 Key Visualizations

- Bar plots of users by age and county
- Line plots of utilization % over time
- Sample X-ray edge detection outputs

## 📚 Report Highlights

- Complete analysis of segmentation, classification, and detection methods
- Panoramic dataset with expert-labeled annotations
- Discussion on limitations, challenges, and future work in dental ML

## 📈 Future Enhancements

- Expand dataset with public, high-resolution annotated X-rays
- Employ hybrid models for improved accuracy
- Automate segmentation with blob detection

---

## 📄 References

- Waugh A., Grant A., Ross and Wilson Anatomy and Physiology
- PMC & PubMed Articles on Dental Caries
- Nature Scientific Reports: YOLO in Dental Imaging

