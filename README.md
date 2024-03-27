Usage:
The system prompts the user to input relevant information, such as age, BMI, glucose level, etc. Based on this input, the system utilizes the trained SVM model to predict the likelihood of the individual having diabetes.

Data:diabetes.csv

The system utilizes a dataset containing information about patients, including features such as:
Pregnancies	Glucose	BloodPressure	SkinThickness	Insulin	BMI	DiabetesPedigreeFunction	Age	Outcome 

Model Training
The SVM model is trained on the labeled dataset, where each instance is associated with a target label indicating the presence or absence of diabetes. The model aims to learn the underlying patterns and relationships in the data to make accurate predictions.

Evaluation
The SVM model's performance is assessed using key metrics:

Accuracy:
Test Data: 77.27%
Training Data: 78.66%
These accuracy scores represent the proportion of correctly classified instances out of the total instances.

