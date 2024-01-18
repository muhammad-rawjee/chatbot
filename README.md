# Customer Service Chatbot
## Description
Built a chat bot that uses a simple two layer Feedforward neural network (FNN), trained on inputs given in ```intents.json```, the program then dumps the trained data on file ```data.pth```. The chatbot uses the trained data to check how similar the users response is to a given ```intent``` and if there is a similarity, the bot generates a response that matches that ```intent or context```, it pulls this response from our ```intents.json``` file. The GUI was built using ```tkinter```
## Installation

### Create an environment
```console
$ cd myproject
$ python3 -m venv venv
```

### Activate it
Mac / Linux:
```console
. venv/bin/activate
```

### Install dependencies
```console
$ pip install -r requirements.txt
```
## Usage
Run
```console
$ python train.py
```
This will dump `data.pth` file. And then run
```console
$ python app.py
```
## Demo
[![](https://markdown-videos-api.jorgenkh.no/youtube/OJG8XA39aas)](https://youtu.be/OJG8XA39aas)


