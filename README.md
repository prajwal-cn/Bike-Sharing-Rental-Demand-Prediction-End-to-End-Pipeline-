# Bike-Sharing-Rental-Demand-Prediction-End-to-End-Pipeline

![image](https://user-images.githubusercontent.com/127007794/230539580-90314795-50e1-4b7b-8db9-526ebd5aa9a0.png)


## **Use case**

Bike sharing systems are a new generation of traditional bike rentals where the whole process from membership, rental and return back has become
automatic. Through these systems, users are able to easily rent a bike from a particular position and return back at another position.
The goal here is to build an end-to-end regression task. Here the user will provide the data and the result will be given by the best performing hyper
tuned Machine Learning model. The user will also get privileges to choose the deployment options.

## **Objective**

The objective of this project is to create a solution for users which can help them to predict demand for rental bikes so that our client can strategically
fulfill their customer demand.

## **Architecture**

![Customer Personality Analysis (1)](https://user-images.githubusercontent.com/127007794/230539540-3f37ecac-2837-42c5-a43a-da4312b422a2.jpg)

## **How to Run**

- Create new env using below command:
- conda create -n env_name python==3.6.9
- Activate your envirnment
- conda activate env_name
- Create MongoDB Database
- Add your mongodb code under constant folder (under init file)
- Run demo.py file to train your model
- Run your app.py file name
- python app.py
- Enter your values and predict the single prediction
- For batch prediction upload dataset from Rental bike demand datafolder
