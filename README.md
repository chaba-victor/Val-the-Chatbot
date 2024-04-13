# Chatbot Deployment with Flask and JavaScript

In this tutorial we deploy the chatbot I created in [this](https://github.com/python-engineer/pytorch-chatbot) tutorial with Flask and JavaScript.

This gives 2 deployment options:
- Deploy within Flask app with jinja2 template
- Serve only the Flask prediction API.

## Setup:

Clone repo and create a virtual environment
```
$ git clone https://github.com/chaba-victor/Val-the-chatbot.git
$ cd Val-the-chatbot
$ python3 -m venv venv
$ . venv/bin/activate
```
Install dependencies
```
$ (venv) pip install requirements.txt
```
Modify `intents.json` to your specific needs

Run the command below. Doing so will dump data.pth
```
$ (venv) python train.py
```
Run the following command to test it in the console.
```
$ (venv) python chat.py
```

## Note
In the video we implement the first approach using jinja2 templates within our Flask app. Only slight modifications are needed to run the frontend separately.
This is a very simple, bare metal implementation of an NLP chatbot with very little training data, so it won't work like the LLMs because it can't. It is however quite useful for simple websites, like single vendor e-commerce sites, when done right.

## Credits:
https://github.com/hitchcliff/front-end-chatjs
