# Car-Price-Prediction
Dataset Link : https://www.kaggle.com/datasets/vishalprasad1/quikr-car-price 

# Demo of GUI
![GUI](https://user-images.githubusercontent.com/122785587/236600995-0ff50435-93fc-40c8-93ae-de5dce01db06.png)

# Aim of the Project
This project aims to predict the Price of an used Car by taking it's Company name, it's Model name, Year of Purchase, and other parameters.

![input](https://user-images.githubusercontent.com/122785587/236601143-2c1eafa5-6329-4205-935c-679150e26f0a.png)

# How to use?
1. Clone the repository
2. Install the required packages in "requirements.txt" file.
3. Run the "application.py" file And you are good to go.

# What this project does?
1. This project takes the parameters of an used car like: Company name, Model name, Year of Purchase, Fuel Type and Number of Kilometers it has been driven.
2. It then predicts the possible price of the car. For example, the image below shows the predicted price of our Hyundai Grand i10.

![predict](https://user-images.githubusercontent.com/122785587/236601352-6c49d386-dfa3-4b75-86d9-c4aeed5c2183.png)

# How this project does?
1. First of all the data was scraped from Quikr.com (https://quikr.com)  

2. The data was cleaned (it was super unclean :( ) and analysed.

3. Then a Linear Regression model was built on top of it which had 0.92 R2_score.

4. Link for notebook:  http://localhost:8888/notebooks/Quicker%20Analysis.ipynb

5. This project was given the form of an website built on Flask where we used the Linear Regression model to perform predictions.
