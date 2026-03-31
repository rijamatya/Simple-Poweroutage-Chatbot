# Simple Power Outage Chatbot

## Project Overview
The Simple Power Outage Chatbot is a domain-specific customer support chatbot designed for electricity service queries such as power outages, billing, safety, and new connections. The chatbot uses Natural Language Processing (NLP) techniques to match user questions with the most relevant answers.

## Technologies Used
- Python
- Pandas
- Sentence Transformers
- Text Embeddings
- Cosine Similarity
- Google Colab

## Dataset
The dataset was manually created as a list of question and answer pairs related to:
- Power outages
- Billing inquiries
- New electricity connections
- Safety tips
- General customer service information

The dataset was then converted into a Pandas DataFrame for processing.

## How the Chatbot Works
1. User enters a question
2. The question is converted into an embedding using Sentence Transformers
3. All stored questions are also converted into embeddings
4. Cosine similarity is calculated between user question and stored questions
5. The most similar question is found
6. The chatbot returns the corresponding answer

## Project Workflow
1. Created manual Q&A dataset
2. Converted dataset into Pandas DataFrame
3. Generated text embeddings using Sentence Transformers
4. Calculated similarity using cosine similarity
5. Returned best matching answer
6. Built a simple chatbot interface

## Features
- FAQ-based chatbot
- Semantic search using embeddings
- Cosine similarity matching
- Electricity customer support chatbot
- Domain-specific NLP chatbot

## Future Improvements
- Add more questions and answers
- Deploy as web application
- Add voice input
- Integrate with live electricity outage data
- Use a large language model for better responses

## Author
Rij Amatya
