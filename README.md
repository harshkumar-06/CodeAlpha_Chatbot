# CodeAlpha_Chatbot

Simple NLP Chatbot

This project is a basic natural language processing (NLP) chatbot developed with Python and NLTK during my internship at [Company Name]. The chatbot can respond to simple greetings, answer basic questions, and recognize when the user wants to end the conversation.
Features

- Greeting Recognition: Responds to "hi," "hello," and other casual greetings.
- Basic Conversational Abilities: Answers questions about its identity and well-being.
- Exit Option: Users can type "quit" to end the conversation.
- Fallback Response: If a question doesn’t match known patterns, it responds with a default message.

How It Works

Using the nltk.chat.util module, this chatbot utilizes regular expressions to match user input against predefined patterns, enabling it to provide appropriate responses.

Sample Interactions

  - Greetings: Try saying “hello” or “hi.”
  - Ask Name: “What is your name?”
  - Exit: Type “quit” to end the session.

Requirements

  - Python 3.x
  - NLTK Library: Natural Language Toolkit (install with pip install nltk)

Future Improvements

  - Expand response options for more conversational topics.
  - Add natural language understanding (NLU) for better responses.
  - Integrate the chatbot with messaging platforms for wider accessibility.
