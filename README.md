# 🌌 NASA Kepler Exoplanet Data Analysis & Classification

## 📌 Project Overview
This project applies Data Analysis and Machine Learning to classify cosmic objects observed by NASA's Kepler Space Telescope. The main goal is to predict whether an observed object is a confirmed planet (`CONFIRMED`) or a false positive signal (`FALSE POSITIVE`).

This system simulates the automated pipeline used by research institutions like KACST to process large-scale astronomical data.

## 🛠️ Tech Stack & Tools
- Language: Python
- Environment: Google Colab
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn (Random Forest Classifier)
- BI Tools: Power BI (Interactive Dashboard)

## 📊 Key Insights & Results
- Model Accuracy: Over 95% in predicting planet validity.
- Top Feature: The Centroid Offset Flag and Planetary Radius were found to be the most critical physical factors in distinguishing real planets from fake signals.

## 🚀 How to Run
1. Open the .ipynb file in Google Colab.
2. Upload the cumulative.csv dataset from Kaggle.
3. Run all cells to see the classification report and charts.
