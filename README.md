# FINAL THESIS OF MASTER DEGREE PROJECT: Prediction of Used Cars Prices

## Project Overview
This project leverages machine learning to predict used cars prices effectively, integrating deep learning and traditional regression methods. We explore different model architectures and enhancement techniques, focusing on the synergistic use of Convolutional Neural Networks (CNN) and Random Forest regressions.

### Repository Structure
This repository contains two detailed Jupyter notebooks which document the methods and analyses used:
- **Price_Prediction_Random_Forest_And_CNN_(Resnet_34)_Comparison.ipynb**:
  Explores the efficacy of CNN and Random Forest models in car price prediction, analyzing their predictive capabilities and suitability based on the data types they process.
  
- **Price_Prediction_Random_Forest_And_CNN_(Resnet_34)_Combinaison_And_Regression.ipynb**:
   Demonstrates how combining these models through transfer learning can significantly improve prediction accuracy.

## Detailed Description of Notebooks

### Price_Prediction_Random_Forest_And_CNN_(Resnet_34)_Comparison.ipynb
- **Data Preparation**: Detailed steps for data loading and preprocessing tailored to each model's needs.
- **Model Building**:
  - **CNN Model**: Utilizes a pre-trained ResNet-34 for feature extraction from car images.
  - **Random Forest Model**: Applies regression analysis to structured data including year, mileage, and more.
- **Performance Evaluation**: Compares model outputs using a range of metrics to highlight each model's strengths and weaknesses.

### Price_Prediction_Random_Forest_And_CNN_(Resnet_34)_Combinaison_And_Regression.ipynb
- **Feature Integration**: Combines features from the CNN with structured data used by the Random Forest.
- **Model Optimization**: Uses GridSearchCV for hyperparameter tuning to optimize the combined model.
- **Evaluation**: Deploys statistical and visual tools to assess model performance and improvements.
