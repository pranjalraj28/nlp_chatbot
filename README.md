# Retrieval Learning Chatbot

This Python code implements a retrieval-based chatbot using Natural Language Processing (NLP) techniques. The chatbot reads and responds to user input based on the content of a provided text file.

## Features

- **Text Processing:** Tokenizes and lemmatizes text data to understand and respond effectively.
  
- **Greeting Recognition:** Recognizes common greetings such as "hello," "hi," and more, providing friendly responses.

- **Response Generation:** Uses TF-IDF and cosine similarity to generate responses by finding the most relevant sentences from the provided text data.

- **Conversation End:** Allows users to gracefully end the conversation by typing "bye."

## Getting Started

1. **Prerequisites:** Make sure you have Python 3.x installed on your system.

2. **Library Installation:** Install the required libraries using pip:
   ```shell
   pip install nltk scikit-learn
<br>

1. Data Preparation: Place the text data you want the chatbot to operate on in a file named 'set_data.txt' in the '/content' directory.
<br>
2. Run the Chatbot: Execute the Python script:


python chatbot.py

3. Start Conversations: Greet the chatbot to initiate conversations. It will respond to your inputs based on the provided data.
<br>
Customization
Data Source: You can replace set_data.txt with your own text data for different chatbot behavior.

Responses: Modify the greet_responses variable to customize greeting responses.
<br>
Author
[Pranjal Raj]
<br>
GitHub: pranjalraj28
<br>
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
This code was inspired by various NLP and chatbot tutorials and resources available online.
Feel free to contribute, report issues, or suggest improvements! We appreciate your feedback.


