# Talking2MultiPDFs

# Overview
In this project, I implemented a chatbot which can read multiple PDFs (imported by user), and answer based on PDFs. I consulted from this github: https://github.com/alejandro-ao/ask-multiple-pdfs

To run this code, after cloning into your local computer, you should create a file ".env", which contains:

```
OPENAI_API_KEY=__YOUR_API_KEY__
HUGGINGFACEHUB_API_TOKEN=__YOUR_API_TOKEN__
```

The API key (OpenAI) and API access token (HuggingFace) can be received from their official websites.

# Details

As following the repo I consulted, I reimplemented the chatbot with OpenAI API + Langchain. Then, the model was changed from OpenAI model to models on HuggingFaceHub, specifically LLama3-8B. However, due to the limited hardware resources, my computer cannot run this model locally (It can run with OpenAI model).

Some UI logics was added to improve UI design, and OOP principles was applied in the code to make it more flexible.
