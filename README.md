## 🎭 Sentiment Analysis of Amazon Product Ratings and Reviews
This project involves analyzing the sentiment associated with reviews and ratings of different products made available by Amazon, using sentiment analysis and machine learning models.

## 📊 Overview

* **Objective**: To analyse sentiments of Amazon products according to user ratings and reviews
* **Dataset**: Dataset of Amazon product ratings and reviews [Kaggle Dataset](https://www.kaggle.com/datasets/tarkkaanko/amazon/data)
* **Tools**: Python (pandas, numpy, scikit-learn, matplotlib, re, nltk, imblearn)

## 💡 Project Highlights

1.  **Data Preprocessing**:
    * Text preprocessing performed by removing punctuations, extra whitespaces, contractions wherever required
2.  **Exploratory Data Analysis (EDA)**:
    * Sentiment Analysis with TextBlob :
    
       * Define a function to classify and analyze overall ratings (>= 4 : positive, <=2 : negative, 3 : neutral)
    
       * Analyze and visualize distribution
    
    * Machine Learning Models (5-fold classification) :
    
      * Support Vector Machine (SVM) : Finding the optimal hyperplane using Linear and Radial Basis Function (RBF) kernels
    
      * Random Forest Classifier : Employed as an ensemble learning method for robust classification
    
      * Naïve Bayes : Cross-validation applied for text classification, leveraging feature-extracted text
    
    * Models trained, tested and evaluated using standard metrics (accuracy, precision, recall, F1-score) and confusion matrices
3.  **Addressing Class Imbalance**:
    * SMOTE (Synthetic Minority Over-Sampling Technique) applied to training data to effectively handle class imbalance (positive vs negative and neutral)
   
    * Synthetic samples generated for minority classes (negative, neutral), thus improving model performance
4.  **Interpretation**:
    * Random Forest Classifier model best fit with 78.54% accuracy among the three models
5.  **Notes**:
    * While VADER is more efficient for nuanced sentiment analysis, TextBlob was chosen for its potential effectiveness in detecting notes of sarcasm and irony.
6.  **Sustainable Development Goals (SDGs)**:
    * **SDG 9** : Industry, Innovation and Infrastructure
   
    * **SDG 12** : Responsible Consumption and Production 
