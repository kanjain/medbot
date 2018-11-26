# medbot
Medical chatbot for SJSU project

# Required dependencies
Pycharm (or any python IDE that can help you set a debugger)
Python 3.6
Flask
requests


# How to debug locally:
1. Install ngrok on local machine. (brew install ngrok)
2. The main.py contains a POST method that is reachable by DialogFlow.
3. The zipcode_converter.py is used to translate zipcode into lat/long
4. The doctor_class.py is used as a class to encapsulate doctor related data from doctor API.

# How to host a local endpoint over https.
ngrok http localhost:5000 -bind-tls=true

You can use this in Fulfillments in DialogFlow and start debugging locally.

