## Heart Disease Risk Predictor
This project focuses on developing an Artificial Neural Network (ANN) model for predicting the presence or absence of heart disease based on relevant patient health information

## Model
This project uses an ANN for binary classification 
The model predicts two possible cases which are either heart or no heart disease
The modeL was trained using a training dataset and tested using a seperated test dataset
The model was evaluated using 
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion matrix
- ROC Curve
- ROC-AUc Curve
This model achieved approximately 98.3% Accuracy and  ROC-AUC of approximately 0.925 on the evaluated set

## Traing Perfomance
The model's training history was monitored using 
- Training and validation loss
- Training and validation accuracy 
- Training and validation AUC
These metrics were visualized across the training epochs to observe the model learned over time 

## Technologies used
All technologies used or modules used can be found in the requirement.txt file

## Streamlit Application
A streamlit application has been developed to allow users to enter the required health information and receive a prediction from a trained ANN model
The application is designed to be accessible through a web browser allowing it to be used on devices such as computers and smartphones

## ⚠️Disclaimer
 This tool is for educational/demonstration purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment. Always consult a qualified healthcare provider.

## Future improvements
- Improve the streamlit user interface
- Deploy the application online for easier access
- Investigate potential data leakage and generalization 
