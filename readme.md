Project Title: Heart Disease Prediction and Analysis

Project Members: Suman K Batra, Kavita Soni, Japjeet Singh

This is Enterprise Computing Project. It demonstrates the use of Web service, Stateless EJB and Weka.
This project strives to understand various traits to predict if a person is likely to have a heart disease or not.

Components of project:
1. Front End ( User Interface )
   Technologies used : HTML, CSS, JAVASCRIPT
 
2. Web Servlet

3. Stateless EJB Module 

4. Machine Learning Module
   Technologies used : WEKA
   
5. Data Exploration and Analysis in Python

6. Different Machine Learning Model Comparison in Python

7. Detailed report of the project

8. Project presentation

9. Project Proposal

Deployment of Project:

This project uses a pre-trained model generated through weka named as heart_model.bin.
To generate the this model, run the KNN project that would create the trained model which can be used further by the Stateless EJB.
The EJB loads the model and makes the prediction for the user input accordingly.
A .war file should be deployed on the server to access the web user interface.

Sample inputs:
age, sex, chestPain, trestbps, cholestrol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal
59,  male, 	 0, 		110, 		239, 	0, 		0, 		142, 	1, 		1, 		1, 	  1, 	3 : Predicts No heart disease
56,	 female, 1,			140,		294,	0,		0,		153,	0,		1,		1,	  0,	2 : Predicts Possibility of heart disease

