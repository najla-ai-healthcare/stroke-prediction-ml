# Stroke Prediction ML Model  

This project builds a Machine Learning model to predict stroke risk using an imbalanced medical dataset.  

## Dataset
- Source: [Kaggle - Stroke Prediction Dataset](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset)  
- Target variable: 'stroke' (1 = stroke, 0 = no stroke).  

## Methods
- Data preprocessing: removed ID column, handled missing values.  
- Algorithms tested: Logistic Regression, Random Forest.  
- Handled imbalance using class weights.  
- Model evaluation: Accuracy, ROC-AUC, Recall, Precision.  

## Results
- **Accuracy**: 0.61
- **ROC-AUC**: 0.78  
- **Recall (Sensitivity)**: 0.84  
- **Precision**: 0.12  

## Tools
- Python  
- Libraries: scikit-learn, pandas, numpy, matplotlib  
- Google Colab  

## How to Run
1. Clone the repo:  

   git clone https://github.com/najla-ai-healthcare/stroke-prediction-ml.git

2.Open predict-stroke in Jupyter or Google Colab
3.Run all the cells

