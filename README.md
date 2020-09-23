# Flight Fare Prediction: 

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Installation](#installation)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)
  * [Technical Aspect](#technical-aspect)
  * [Technologies Used](#technologies-used)
  * [Team](#team)
  * [Future scope of project](#future-scope)


## Demo
Link: [https://flightpricetest.herokuapp.com/](https://flightpricetest.herokuapp.com/)

[![](https://i.imgur.com/H2ySzdD.png)](https://flightpricetest.herokuapp.com/)

[![](https://i.imgur.com/obTab5p.png)](https://flightpricetest.herokuapp.com/)

## Overview
This is a Flask web app which predicts fare of Flight ticket.

## Motivation
As a Data Science enthusiast I am utilizing the lockdown period with implementing various machine learning and deep learning projects and try to do end to end projects,also writing blogs on my data science projects on medium (Link: [https://medium.com/analytics-vidhya/implementing-lstm-for-stock-price-prediction-time-series-4c0c65bb493d/](https://medium.com/analytics-vidhya/implementing-lstm-for-stock-price-prediction-time-series-4c0c65bb493d/))

## Installation
The Code is written in Python 3.6.10. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Directory Tree 
```
├── datasets
│   ├── Flight_test.xlsx
│   ├── Flight_train.xlsx
├── static 
│   ├── style.css
├── template
│   ├── home.html
├── Procfile
├── README.md
├── app.py
├── Project_17.ipynb
├── flight_rf.pkl
├── requirements.txt
```

## Technical Aspect

1. Training a machine learning model.
2. Building and hosting a Flask web app on Heroku.
3. Used Multiple algorithms to train the model.
4. Used Hyperparameter tunning to enchance the performance of model.
5. Done visualization using libraries seaborn, matplotlib and plot univariate,bivariate graphs.
6. Done Feature Selection and EDA(data exploration).

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 


## Team

Mayank Yogi

## Future Scope

* Use multiple Algorithms
* Optimize Flask app.py
* Front-End 
