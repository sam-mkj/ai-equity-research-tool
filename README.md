
# Equity Research Tool 

A simple and intuitive news research tool that makes information retrieval seamless. By entering article URLs, users can ask questions and quickly gain valuable insights related to the stock market and broader financial topics.

## Features

- Import URLs directly or upload text files containing them to extract article content.
- Use LangChain’s UnstructuredURL Loader to process and structure the retrieved content.
- Generate embedding vectors with OpenAI embeddings and apply FAISS for fast, accurate similarity-based information retrieval.
- Engage with the LLM (ChatGPT) by submitting queries and receiving contextual answers paired with source URLs.

## Project Structure

- main.py: The main Streamlit application script.
- requirements.txt: A list of required Python packages for the project.
- faiss_store_openai.pkl: A pickle file to store the FAISS index.
- .env: Configuration file for storing your OpenAI API key.
