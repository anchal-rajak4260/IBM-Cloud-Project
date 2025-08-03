# IBM-Cloud-Project
<-------------4TH - AUGUST - 2025----------->
IBM Cloud project details and files as well the complete project details is here

Develop a predictive maintenance model for a fleet of industrial machines to anticipate failures before they occur. This project will involve analyzing sensor data from machinery to identify patterns that precede a failure. The goal is to create a classification model that can predict the type of failure (e.g., tool wear, heat dissipation, power failure) based on real-time operational data. This will enable proactive maintenance, reducing downtime and operational costs. 
Objective: Develop a predictive maintenance model to anticipate machine failures. 
Challenge: Use sensor data to identify patterns that precede failures. 
Target : Failure or Not
Failure Type : Type of Failure
Impact: Reduce downtime and operational costs through proactive maintenance. 

ALGORITHM AND DEVELOPMENTS:-
Algorithm Selection:
Random Forest Classifier, Logistic Regression.
tool wear, heat dissipation, power failure.
Failure vs. No Failure and Overstrain Failure
Data Input:
UID: unique identifier ranging from 1 to 10000
Product ID: consisting of a letter L, M, or H for low (50% of all products), medium (30%), and high (20%) as product quality variants and a variant-specific serial number
air temperature [K]: generated using a random walk process later normalized to a standard deviation of 2 K around 300 K
process temperature [K]: generated using a random walk process normalized to a standard deviation of 1 K, added to the air temperature plus 10 K.
rotational speed [rpm]: calculated from power of 2860 W, overlaid with a normally distributed noise
tool wear [min]: The quality variants H/M/L add 5/3/2 minutes of tool wear to the used tool in the process. and a
Training Process:
'machine failure' label that indicates, whether the machine has failed in this particular data point for any of the following failure modes are true.
Prediction Process:
Algorithm makes predictions for Continuous input from live sensors (temperature, vibration, pressure) 
Streaming data processed via edge computing or cloud platforms.
