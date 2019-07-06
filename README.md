


Updated Readme


# Chatbots Bring Revenue
Chatbots have proven to be successful in bringing more revenue to the business. Businesses starting with chatbot support or creating a new chatbot to support customer queries are doing well in the market compared to their competitors.
# 
# Customers Prefer Chatbots
Chatbots are not just software in the modern era. Chatbots are like our personal assistants who understand us and can be microconfigured. They remember our likes and dislikes and never tend to disappoint us by forgetting what we taught them already, and this is the reason why everyone loves chatbot. Next time you meet a person or meet your customer, don’t forget to ask if they prefer conventional software or the new cutting-edge chatbots. 

# What Kind of Problems Can I Solve Using Chatbots?
This question becomes challenging when you don’t know the scope of your bot or don’t want to limit it to answer queries.
It’s very important to remember that there is a limit to what chatbots can do. It always feels that we are talking to a human-like thing that is very intelligent, but the specific bot is designed and trained to behave in a certain way and solve a specific problem only. It cannot do everything, at least as of now. The future is definitely bright.

# First chatbot is online food ordering system
•	https://dialogflow.com/ 
•	Formerly known as api.ai and widely popular among chatbot enthusiasts.
•	Give users new ways to interact with your product by building engaging voice-and text-based conversational interfaces powered by AI.
•	Connect with users on the Google Assistant, Amazon Alexa, Facebook Messenger, and other popular platforms and devices.
•	Analyzes and understands the user’s intent to help you respond in the most useful way.

# Installation and Prerequisites 


You can use whichever version of Python you are comfortable with. Most of the systems today come pre-installed with default Python version 2.7.x. We’ll be using Python 3 in this chapter. So, if you want to use Python 3, please install Python 3 on your operating system by downloading it from https://www.python.org/downloads/. If you have Python 2 installed already, you can use that as well; it may or may not need minor code changes.
We will install spaCy via pip [2].
We are going to use a virtual environment [3] and install spaCy into a user directory.
If you are on macOS/OSX/Linux, follow these steps:
Step 1: python3 -m pip install -U virtualenv
Step 2: virtualenv venv -p /usr/local/bin/python3 #Make sure you use your  own OS path for python 3 executable.
Step 3: source venv/bin/activate Step 4: pip3 install -U spacy # We'll be using spaCy version 2.0.11.

# Building Chatbots the Easy Way
# Introduction to Dialogflow 
  Dialogflow gives users new methods to interact with their product by building engaging voice- and text-based conversational interfaces, such as voice apps and chatbots. Dialogflow is powered by AI. It helps you connect with users on your website, mobile app, the Google Assistant, Amazon Alexa, Facebook Messenger, and other popular platforms and devices.

# Building a Food-Ordering Chatbot
We are going to create a chatbot with help of Dialogflow for a specific restaurant. Let’s name it OnlineEatsBot. In short we can call it OnlineEats product. You can choose any other use-case for which you want to build the chatbot. For this chapter we are going to build a food-ordering chatbot.

Chatbot and User Conversation Script:
  User: Hello
  OnlineEatsBot: Hello and Welcome! How may I help you?
  User: I am looking to order Chinese food.
  OnlineEatsBot: Sure, what would you like to order today?
  User: One chicken dumpling and two spring rolls.
  OnlineEatsBot: Done. Your final amount is XYZ, and your order is placed for 1 Chicken dumpling and 2 spring rolls.
  User: I haven’t received my order yet. Where is my food?
  OnlineEatsBot: Can you please help me with your order ID?
  User: 123456
  OnlineEatsBot: Order Status for Order ID: 123456. The delivery guy is in your locality, your food will arrive in about 5 minutes.
  User: Thanks.



# horoscope-bot
