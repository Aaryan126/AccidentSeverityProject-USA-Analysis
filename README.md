# Accident Severity Prediction Model for Resource Allocation
All code available inside Notebook.ipnyb
## Problem Statement
Efficient resource allocation is crucial for medical services to respond effectively to accidents, especially those with greater severity. This project addresses the challenge of optimizing resource allocation by creating a prediction model that anticipates the severity of accidents in New York City.

## Objective
The primary objective of this project is to develop a prediction model that utilizes both categorical and numerical data to accurately predict the severity of accidents. By doing so, medical services can allocate their resources more efficiently and prioritize responses to incidents with higher severity.

## Models Used
Three machine learning models were employed in this project:

Decision Tree
Support Vector Machine (SVM)
Random Forest
#Results
After rigorous evaluation, the Random Forest model emerged as the most accurate predictor of accident severity. This model not only demonstrated superior overall accuracy but also provided valuable insights into feature importance.

Random Forest Feature Importance:

Distance: The distance of road affected due to the accident.
Start_Lat and Start_Lng: Location coordinates, indicative of road infrastructure.
Pressure, Temperature, and Humidity: Environmental factors affecting tire grip, braking, visibility, and road surface conditions.
Understanding these important features helps in identifying key contributors to accident severity and guides resource allocation strategies.

## Practical Solution
The prediction model offers practical solutions in real-life scenarios:

Accident Hotspot Identification: The model assists in identifying areas with a high frequency of accidents. Authorities can use this information to implement targeted safety measures in specific locations.

Emergency Response Planning: Emergency response personnel can leverage the model to prioritize accidents based on severity in different locations. This aids in decision-making during emergency responses, ensuring that resources are allocated efficiently.
