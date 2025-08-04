# IBM-Cloud-Project


This repository contains my internship project at IBM Cloud, where I built a Machine Learning model using no-code tools via IBM Watson Studio. The project was completed through the UI interface without writing any code, leveraging IBM's cloud-based tools for data analysis, model training, and deployment.

## 🚀 Project Overview

- Project Title:Power system Fault detection and classification using machine learning
- Internship Domain: IBM Cloud and AI Technologies
- Project Type: No-Code, UI-based Machine Learning
- Platform Used: IBM Watson Studio (Cloud)
- Tools Used:  IBM Cloud Object Storage, IBM Watson Machine Learning

## 🧠 Project Objective

The goal of this project was to develop a machine learning model to detect and classify different types of faults in a power 
distribution system. Using electrical measurement data (e.g., voltage and current 
phasors), the model should be able to distinguish between normal operating conditions 
and various fault conditions (such as line-to-ground, line-to-line, or three-phase faults). 
The objective is to enable rapid and accurate fault identification, which is crucial for 
maintaining power grid stability and reliability. using IBM’s no-code platform.

## 🗃 Dataset

- Source: https://www.kaggle.com/datasets/ziya07/power-system-faults-dataset
- Format: CSV

## 🛠 Steps Followed

1. Created a Project in IBM Watson Studio
   - Selected the "Create project" option and chose "Machine Learning".
   - Attached IBM Cloud Object Storage.

2. Uploaded Dataset
   - Uploaded the dataset in .csv format to the Cloud Object Storage bucket.
   - Added the dataset as an asset in the project.

3. Used AutoAI for Model Building
   - Clicked "Add to project" > "AutoAI experiment".
   - Selected the dataset and target column for prediction.
   - AutoAI explored multiple pipelines and built different models automatically.

4. Model Selection
   - Evaluated models based on accuracy, ROC-AUC, etc.
   - Chose the best-performing model as suggested by AutoAI.

5. Model Deployment
   - Deployed the selected model as a web service using Watson Machine Learning.
   - Obtained a REST endpoint for model inference.

6. Model Testing
   - Used the UI to test the model with sample data.
   - Verified the results visually and through predictions.


## ✅ Key Learnings

- Hands-on experience with IBM Watson Studio’s no-code ML features.
- Understanding how AutoAI works and selects models/pipelines.
- Familiarity with deploying ML models via UI without coding.
- Using cloud-based services like IBM Cloud Object Storage and Watson Machine Learning.

## 🌐 Deployment

- Model Deployed As: Web Service (REST API)
- Deployment Platform: IBM Watson Machine Learning

## 🧾 Conclusion

This project helped me understand the end-to-end ML lifecycle using IBM Cloud without writing a single line of code. It showcases how powerful UI-based tools can democratize AI development.

