# Alzheimer-Prediction-Model

This project is not created for medical purposes. 

1. Demographic Information in the datataset

Age: The age of the participant. This is the strongest predictor of Alzheimer's risk in our model.

Gender: The participant's gender (0: Male, 1: Female).

Education Level: Total years of completed education.

Urban vs Rural Living: The type of area the participant resides in (0: Urban, 1: Rural).

2. Lifestyle and Habits

Physical Activity Level: Intensity of weekly exercise (0: Low, 1: Medium, 2: High).

Smoking Status: History of tobacco use (0: Never, 1: Former, 2: Current).

Alcohol Consumption: Frequency of alcohol intake (0: Never, 1: Occasionally, 2: Regularly).

Dietary Habits: Quality of the participant's diet (0: Unhealthy, 1: Average, 2: Healthy).

Sleep Quality: General quality and consistency of sleep (0: Poor, 1: Average, 2: Good).

Social Engagement Level: Participation in social activities (0: Low, 1: Medium, 2: High).

3. Medical & Clinical Indicators

BMI (Body Mass Index): Ratio of weight to height. This was the second most important feature in our analysis.

Cognitive Test Score: A measure of mental performance (range: 30-99). Lower scores indicate higher risk.

Diabetes: Presence of a diabetes diagnosis (0: No, 1: Yes).

Hypertension: High blood pressure status (0: No, 1: Yes).

Cholesterol Level: Blood cholesterol status (0: Low, 1: Medium, 2: High).

Depression Level: Measure of psychological state (0: Low, 1: Medium, 2: High).

Stress Levels: Reported stress levels (0: Low, 1: Medium, 2: High).

4. Genetic & Environmental Factors

Genetic Risk Factor (APOE-ε4 allele): Presence of the most common genetic risk variant for Alzheimer's (0: No, 1: Yes).

Family History of Alzheimer’s: History of the disease in first-degree relatives (0: No, 1: Yes).

Air Pollution Exposure: Exposure to environmental toxins based on location (0: Low, 1: Medium, 2: High).

5. Target Variable

Alzheimer’s Diagnosis: The outcome the model is predicting (0: Not Diagnosed, 1: Diagnosed).

Created Model: Random Forest Classifier.
