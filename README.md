# Foodie Restaurant Bot

An Indian startup named 'Foodie' wants to build a conversational bot (chatbot) which can help users discover restaurants across several Indian cities. 

The main purpose of the bot is to help users discover restaurants quickly and efficiently and to provide a good restaurant discovery experience. 

Work only in Tier-1 and Tier-2 cities.

Zomato API used for searching the restaurants. https://developers.zomato.com/documentation#/


YOUTUBE VIDEO LINK: https://www.youtube.com/watch?v=qCqi8b77SMY&feature=youtu.be



### Prerequisites

python 3.6.x(except 3.6.6)
Visual studio for python development 
rasa                               1.10.1
rasa-sdk                           1.10.1
rasa-x                             0.28.3

### Installing ---- How to Run:


## What to Install

## Virtual Environment

`Creating virtual environment for this project with anaconda using the below command`
`conda create -n yourenvname python=x.x anaconda`
`After creating the virtual env type conda activate yourenvname to activate it`
`Then install rasa using the following commands`

#### Install Rasa and Rasa X

`You can install both Rasa and Rasa X using the following code:`
`$ pip install rasa-x --extra-index-url https://pypi.rasa.com/simple`

#### Install Rasa NLU and spacy

```
$ pip install rasa[spacy]

$ python -m spacy download en_core_web_md

$ python -m spacy link en_core_web_md en
```

## Train the nlu data & train the core conversational flow using command line

cd path <path to project>

### train the NLU
$ rasa train nlu

### train Core
$ rasa train core

### Run Dialogue management
	
	Step 1: run the action server
	```
		rasa run actions
	```
	Step 2: run the RASA shell
	```
		rasa shell
	```

### Slack Integration
	```
	Step 1: Register new app in slack
		https://api.slack.com/apps
	
	Step 2: Add OAuth & Permissions to register the app

	Step 3: Install App
	
	Step 4: Go to Event Subscriptions
		Add action endpoint url

	Step 5: Go to your slack workspace and chat with the bot
	```


## Train the nlu data & train the core conversational flow using python code

cd path <path to project>

### train dialogue flow online and add the strories

$ rasa interactive

```
Generated stories can be exported to a path and then added to stories.md. Retrain the model and check dialogue flow.
```

## Deployment to slack

run the bot on local sever and integrate with slack.

Using ngrok (https://ngrok.com/download) as a webhook deploy the bot on slack(https://slack.com/). Create a bot in slack and integrate the credentials in run_app.py program.

$python .\run_app.py  

Bot can be accessed from slack. 

 

## Built With

* Rasa
* Keras Framework
* Tensorflow
* Slack


## Authors

* **Shashi Teja Tripurari**
* **Ayushi Sharan**

# ChatBot
