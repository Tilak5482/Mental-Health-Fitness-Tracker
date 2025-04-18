# Mental-Health-Fitness-Tracker
This is a simple mental health chatbot built using Python and the Natural Language Toolkit (NLTK) library. The chatbot is designed to listen to user input and provide appropriate responses based on the sentiment of the input. The sentiment analysis is done using the TextBlob library.
<h1><b>Implementation</b></h1>
The chatbot is built using the Python programming language and several libraries, including nltk, textblob, and transformers. The chatbot can be run in a command-line interface (CLI), allowing users to interact with the bot using natural language.

The first step in building the chatbot is to install the required libraries. This can be done using the pip package manager. The required libraries are:

1. transformers
2. torch
3. textblob
4. nltk

Once the libraries are installed, we can begin writing the code for the chatbot. The chatbot consists of two main parts: a pattern matching component and a sentiment analysis component.

The pattern matching component is responsible for recognizing and responding to specific patterns in the user's input. For example, if the user says "hi" or "hello", the chatbot will respond with a greeting. We define a list of pairs, where each pair consists of a regular expression pattern and a list of possible responses. The nltk library provides a Chat class that allows us to easily define and use these pattern-response pairs.

The sentiment analysis component is responsible for determining the sentiment of the user's input. We use the textblob library to perform sentiment analysis, which returns a sentiment score between -1 and 1, where -1 is very negative, 0 is neutral, and 1 is very positive. We define a function that takes in a string of text and returns a string representing the sentiment.

The get_response function takes in the user's input and uses the sentiment analysis function to determine the sentiment. Based on the sentiment, the function returns a response that is appropriate for that sentiment. For example, if the sentiment is very negative, the response might be to suggest that the user contact a mental health professional.

The chat function is the main function that runs the chatbot. It starts by greeting the user and then enters a loop, where it prompts the user for input and responds accordingly. If the user types "quit", the loop exits and the chatbot says goodbye.

![image](https://user-images.githubusercontent.com/102237174/236987363-4b1431e9-9c95-4f06-8397-f8ae89e51a9f.png)


<h1><b>Installation</b></h1>
<ol>
  <li>Clone the repository to your local machine.</li>
  <li>Install the required packages using pip:</li>
  <ul>
    <li>pip install transformers</li>
    <li>pip install torch</li>
    <li>pip install textblob</li>
    <li>pip install nltk</li>
  </ul>
    <li>Run the chatbot using the command: python chatbot.py</li>
    
</ol>

<h1><b>Usage</b></h1>
  <ol>
    <li> When the chatbot is running, it will display a greeting message and wait for your input.</li>
    <li>Type your message and press Enter to send it to the chatbot.</li>
    <li>The chatbot will respond with an appropriate message based on the sentiment of your input.</li>
    <li>If you want to quit the chatbot, type "quit" and press Enter.</li>
  </ol>


