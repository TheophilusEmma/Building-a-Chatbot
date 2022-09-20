# Building-a-Chatbot
Here's a chatbot trained using neural networks, coupled with a GUI, for user interaction.
The application of this system can be used in different fields such as Healthcare, commerce and in application that aid in assisting a person.

This one is aimed in working in the health care sector. 
More updates are to be added.

A Chatbot is an intelligent piece of software that is capble of communicating and performing actions similar to a human. Chatbots are used a lot in customer interaction, marketing on social network sites and instantly messaging the client.
There are two basic types of chatbot models based on how they are built;
  a) Retrieval based chatbots:
  b) Generative based chatbots

Retrieval based chatbots- usess predefined input patterns and responses. It then uses some type of heuristic approach to select the appropriate response. It is widely used in the industry to make goal-oriented chatbots where we can customize the tone and flow of the chatbot to drive our customers with the best experience.

Generative models are not based on some predefined responses. They are based on sequence to sequence neural networks. It is the same idea as Machine Transalation, we translate the source code from one language to another language but here, we are going to transform input into an output. It needs a large amount of data and it is based on Deep Neural networks.

In this project, we are going to build a chatbot using deep learning techniques. The chatbot will be trained on the dataset which contain categories (intents), patterns and responses. 
We are using a special recurrent neural network (LSTM) to classify which category the user's message belongs to and then we will give a random response from the list of responses.

Let's create a retrieval based chatbot using NLTK, Keras, Python etc.
