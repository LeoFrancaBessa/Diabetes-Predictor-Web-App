# Diabates Predictor Web App :brazil: 

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Technologies Used](#technologies-used)
  * [Technical Aspect](#technical-aspect)
  * [Machine Learning Model](#machine-learning-model)
  * [Data Collection](#data-collection)
  * [Team](#team)
  * [Credits](#credits)

## Demo
Link: [https://diabates-predictor.herokuapp.com/](https://diabates-predictor.herokuapp.com/)

[![](https://i.imgur.com/54J9Prl.png)](https://diabates-predictor.herokuapp.com/)

## Overview
This is a classifation app build in the Django Framework. The trained model takes the informations about the pacient as a input, and predict the class: Diabetes or Healthy.

## Motivation
In this lockdown period, people are afraid to go to medical appointments for fear of contracting the new coronavirus, and because of that, many diseases can go unnoticed. With this app, people can know if they have a high chance of having diabetes without leaving home, the only thing they need to do is put their information on the website and wait for the result.


## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/1280px-Scikit_learn_logo_small.svg.png" width=200>](https://scikit-learn.org/stable/) [<img target="_blank" src="https://cdn.iconscout.com/icon/free/png-512/django-2-282855.png" width=170>](https://www.djangoproject.com/) [<img target="_blank" src="https://rapids.ai/assets/images/xgboost_logo.png" width=280>](https://xgboost.readthedocs.io/en/latest/) [<img target="_blank" src="https://cdn.iconscout.com/icon/free/png-512/heroku-5-569467.png" width=200>](https://dashboard.heroku.com/apps) 


## Technical Aspect
This project is divided into two parts:
1. Training a machine learning model using Sk-learn.
2. Building and hosting a Django web app on Heroku.


## Machine Learning Model
In this classification problem, a voting classifier based on: XGBoost, SVM's, Extra Trees and Random Forests was used to predict the class. For more information about the code and the techniques used, check out the Jupyter notebook in the "Machine Learning Model Folder".


## Data Collection
The dataset used was the Pima Indians Diabetes Database, available on [Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database)


## Team
[![Leonardo França Bessa](https://avatars2.githubusercontent.com/u/22757584?s=460&u=34b2e3fde44b13d47ce00e372cf66db078a8e300&v=4)](https://www.linkedin.com/in/leonardo-fran%C3%A7a-2246641a3/) |
-|
[Leonardo França Bessa](https://www.linkedin.com/in/leonardo-fran%C3%A7a-2246641a3/) |)

## Credits
- [Creating a Machine Learning Based Web Application Using Django](https://towardsdatascience.com/creating-a-machine-learning-based-web-application-using-django-5444e0053a09): Withouth this amazing tutorial on how to build a app using Django, I wouldn't be able to develop this.
