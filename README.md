# BodyFatCalc
This application predicts body fat percentage based on various body measurements and personal details. It uses a trained machine learning model to estimate body fat percentage from input data.
# How It Works
## Data Preprocessing:
- The data is loaded from a CSV file.
- Features such as Body Mass Index (BMI), Abdomen-to-Chest ratio (ACratio), and Hip-to-Thigh ratio (HTratio) are calculated.
- Outliers are removed based on z-scores to clean the data.
## Model Training:
- The cleaned data is split into training and testing sets.
- A linear regression model is trained on the transformed data.
## Prediction:
- Input data is transformed and passed through the trained model to predict body density.
- The body fat percentage is calculated using the predicted density.
