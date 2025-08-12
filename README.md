# Fuel Efficiency Prediction with TensorFlow and Keras

This project predicts a car’s **fuel efficiency (Miles Per Gallon - MPG)** using **machine learning models** implemented in **TensorFlow/Keras**.  
It uses the classic **UCI Auto MPG Dataset**, performs data cleaning and preprocessing, trains a regression model, and evaluates the results.

By estimating vehicle MPG from specifications before manufacturing, this model can aid in **design optimization** and **emissions reduction**.

---

## Dataset
- **Source:** [UCI Machine Learning Repository — Auto MPG](https://archive.ics.uci.edu/ml/datasets/auto+mpg)
- **Instances:** 398 records
- **Features:**
  - Cylinders
  - Displacement
  - Horsepower
  - Weight
  - Acceleration
  - Model Year
  - Origin (categorical)
- **Target:** MPG (continuous variable – numeric fuel efficiency value)

---

## Project Workflow
1. **Data Loading & Exploration**
2. **Data Cleaning & Preprocessing**
   - Handle missing values
   - Normalize numeric features
   - Encode categorical variables
3. **Model Building**
   - Regression model using TensorFlow/Keras
4. **Model Evaluation**
   - Metrics: Mean Absolute Error (MAE)
   - Visualization of loss/prediction accuracy
5. **Prediction & Interpretation**
   - Predictions on unseen data

---

## Example Outputs
- Data distribution plots
- Correlation heatmaps
- Training & validation loss curves
- Example predictions with MAE score



