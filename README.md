#The "AI Doctor" application provides a user-friendly interface for predicting diseases based on symptoms. It leverages a Support Vector Classifier (SVC) model, trained on a dataset of symptoms and corresponding diseases, to make predictions.

Key Features:

Symptom Input: Users can input their symptoms as a comma-separated string through a web form or can use voice recognition.
Disease Prediction: The application processes the input, converts it into a numerical vector, and feeds it to the trained SVC model to predict the most likely disease.
Detailed Information: Upon prediction, the application retrieves and displays detailed information about the predicted disease, including:
Description,
Precautions,
Medications,
Dietary recommendations,
Workout recommendations.
Model Loading: The pre-trained SVC model is loaded from a pickle file.
Workflow:

The user enters symptoms through the web form.
The application processes the input, converting it into a numerical vector.
The trained SVC model predicts the disease.
The application retrieves and displays detailed information about the predicted disease.
Technical Details:
Flask,
NumPy,
Pandas,
Pickle,
Machine Learning Model: Support Vector Classifier (SVC),
Data Source: CSV files.

