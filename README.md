# Chatbot-using-chatterbot library and flask framework.

1. What is a ChatBot?

  A chatbot is a computer program that conducts the conversation between the user and a computer by using textual or auditory means. It works as a real-world conversational       partner.

  You have seen different chatbots in your life Siri, Cortana, Alexa, and so forth. As per a review, the chatbot is required to finish around 80% of all works in the coming       decades. Presently, chatbots are practically finishing 30% of the tasks. With the expanding boom, it has turned out to be imperative to learn Machine Learning and Artificial     Intelligence.


2. Working of ChatterBot:

  First, the chatbot is trained with a set of training data present in /data directory and creates a sqlite3 database. When the users inputs a query the bot searches for a         response from the database if it finds an answer then it prints the response or else it will search for an answer from Wikipedia using web scraping and provide an appropriate   response.

  The chatterbot works in the following manner:

  >Get the input from the user.
  >Process the input.
  >Returns the value that is generated with the highest confidence value.
  >Return the response to the user.

3. Working of the Project:

  First, the chatbot is trained with a set of training data present in /data directory and creates a sqlite3 database. When the users inputs a query the bot searches for a         response from the database if it finds an answer then it prints the response or else it will search for an answer from Wikipedia using web scraping and provide an appropriate   response.

  Getting Started:

  These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. Make sure you have Python installed on your     machine.

  Setting up the Project:

  >Clone the repository using
   git clone https://github.com/Abhishek-hash/chat-bot.github.io
  >Open the terminal/cmd and navigate to the project folder.
   cd ChatBot-Flask
  >Install the requirments.txt using
   pip install requirments.txt
  Requirments.txt will install all the required dependancies.

4. Usage:

  Now run the chatbot.py using:
  python chatbot.py
  Congrats! The app should now be running on http://localhost:5000

  Open http://localhost:5000 in your browser to interact with the chatbot.
