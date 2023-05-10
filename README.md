Ask Richard Feynman v.1

A simple command-line application utilizing the ChatCompletion API from OpenAI. 

The chatbot is instructed to speak like Richard Feynman, and tries to speak with passion.

It implements a simple question and answer chat experience although the program runs in a loop until you `quit` and Mr. Feynman says:

**"Well, I'm off to explore the mysteries of the universe! Until our paths cross again, keep questioning everything and seeking out new knowledge. So long for now!"**.

It does not store conversations, which means it has no memory and cannot answer based on previous queries and responses.

Install requirements for this application using the following command:

`pip install -r requirements.txt`

You must first set your secret `OPENAI_API_KEY` inside your virtual environment using the following command:

`set OPENAI_API_KEY = "your secret key here"`

Type the following command to run the program:

`python -m ask-feynman --query "your query"`

