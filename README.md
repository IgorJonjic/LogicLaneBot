# LogicLaneBot

This repository is a showcase of artificial intelligence and natural language processing.
It contains chatbot model that is trained to recognize intents of users and respond correctly.
For this small demo bot understands greetings and goodbyes as well as users moods and will respond accordingly.

It can easily be extended to recognize more intents just by adding more intents in intents.json file.


# How to use

1. Create conda environment from environment.yml file or make python venv from requirements.txt

For demo:
 1. run main.py

For extending bot capabilities:
 1. add new intents to intents.json
 2. run preproces_bow.py
 3. run main.py


This repository could be used as good starting point to develop chatbots that could be used in real life scenarios,
or could be used for learning and trying out different preprocessing methods and neural net architectures.
