# Mental HealthCare ChatBot

LLama2HealthCareChatBot is a conversational AI chatbot designed to assist mental healthcare queries and help in providing mental health information, answering queries, and offering support related to various topics relating to psychological well being.

The photo in MH bot.png displays how the bot looks like and functions . The user can clone this repository and download the LLM model (any llama 2 model from huggingface) , to build their own versions of the same .

The data used for training the model is sourced from a paper titled "Defining mental health and mental illness" published by Sharon Leighton and Nisha Dogra .
[Dogra, N., & Cooper, S. (2017). Defining mental health and mental illness. In Psychiatry by Ten Teachers (pp. 15-25). CRC Press.]

The project also uses Langchain and Llama 2 framework to run the LLM model on CPU . It uses langchain to generate chunks of text data , and create embeddings and then train it on the LLM .
