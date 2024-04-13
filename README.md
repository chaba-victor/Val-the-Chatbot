# Chatbot with Flask and JavaScript

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
This is a very simple, bare metal implementation of an NLP chatbot with very little training data, so it won't work like the LLMs because it can't. It is however quite useful for simple websites, like single vendor e-commerce sites, when done right.

## Credits:
https://github.com/hitchcliff/front-end-chatjs
