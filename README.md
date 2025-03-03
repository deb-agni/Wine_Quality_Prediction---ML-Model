# Wine_Quality_Prediction---ML-Model
It is a regression and classification based ML model used for "Quality Prediction of Wine" by using the physiochemical qualities of the wine.
This model is based upon a real life based dataset containing ( 6497 rows  * 12 columns).
Here we used "RandomForestClassifier model" which results the highest accuracy among the other regression or classifier model. 
In the model we classified the output as Binary output { 0 : quality<=6, 1 : quality>=7 }
In the deployment section the binary output is convert into a text message which tell the is upto mark or not.

---

**Project Title:** Wine Quality Prediction

## Description
This project aims to predict the quality of wine using machine learning models based on various chemical properties of wine. Several models are trained and evaluated to determine the most effective one for classification.

## Dataset
The dataset consists of multiple features related to wine composition, such as acidity, alcohol content, and sugar levels. The goal is to classify wine quality based on these attributes.

## Installation & Requirements
Ensure you have the following dependencies installed before running the notebook:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```
Check the notebook for any additional required libraries.

## Usage
1. **Data Collection:** Load and explore the dataset.
2. **Feature Engineering & Selection:** Process data to extract relevant features.
3. **Exploratory Data Analysis (EDA):** Visualize key patterns and correlations.
4. **Train-Test Split & Scaling:** Prepare the dataset for model training.
5. **Model Training & Evaluation:** Train multiple models, including:
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier
   - Support Vector Classifier (SVC)
   - K-Nearest Neighbors (KNN)
6. **Model Deployment:** Implement the best-performing model for predictions.

## Results
The project evaluates various models based on accuracy and performance metrics, selecting the most effective model for predicting wine quality.

## Contributors
- Deb Agni Patra

## License
This project is for educational purposes. You may modify and use it as needed.

