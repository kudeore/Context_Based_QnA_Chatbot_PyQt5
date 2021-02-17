# Context_Based_QnA_Chatbot_PyQt5
Question answering Chatbot craeted by using PyQt5 tools, for questions related to particular context 


## Content
  * [Visuals](#Visuals)
  * [Context](#Context)
  * [Cloud Deployment Heroku ](#Cloud_Deployment_Heroku)
  * [Directory Tree](#directory-tree)
  * [Am I missing Something?](#Am-I-missing-Something?)


## Visuals
Link:https://airfarepred.herokuapp.com/


[<img target="_blank" src="https://i.imgur.com/Rx9nN7t.png" width=600 height=500>]


## Context
- Here wiki page of Elon Musk is taken as a context to be feed to the transfomers 
- Other contexts such as Books or any other liturature can be given as context , to build QnA bot 

[<img target="_blank" src="https://i.imgur.com/gVj7M10.png" width=400 height=200>]



## Installation
-Install all dependancies using following command after cloning [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```
- One needs PyQt5 to be installed to run QnA framework
- this can be installed through .exe file attahced with repo. 

## Deployement on Heroku
- Signup on heroku.com 
- To deploy on heroku we need heroku ctl to be downloaded 

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

- Next step is to create heroku app with name as per availability 
- We need to push the code on heroku using Git commit 
- detail steps are given in the documentation (for documentation visit Heroku website) 
- [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python)

Importatnt Things to make note of while deploying model to Heroku free cloud . 
- Heroku provides max 500MB sludge memory 
- If we have big model , its not possible to deploy it on Heroku Cloud. 


## Directory Tree 
```
├── static 
│   ├── css
│      ├── style.css
├── images 
│   ├── flight.jpeg
├── templates
│   ├── home.html
├── Preprocessing.py
├── feature_selection.py
├── app.py
├── Procfile
├── README.md
├── model.pkl
├── requirements.txt
```

- model.pkl is not copied to repo , as size is to huge 
- Please run Preprocessing.py in your local machine first to get model.pkl 

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://i.imgur.com/Vgxcuk1.png" width=170>]
[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 


## Am I missing Something?

- **Nothing is impossible!**
- please open an [issue](https://github.com/kudeore/Flight_price_pred_AWS_APP/issues) and lets make it better together 
- *Bug reports, feature requests, patches, and well-wishes are always welcome.* :heavy_exclamation_mark:
