# Mercor_project # AI Semantic Search

This project demonstrates AI-powered semantic search using Pinecone, Sentence Transformers, and Gradio.

## Description

The AI Semantic Search project enables you to search for similar sentences based on a query using vector embeddings. It uses the BERT-based Sentence Transformers model to encode the sentences into vectors, stores them in a Pinecone index, and retrieves the most similar sentences based on the query.

## Installation

1. Install the required packages:

pip install pinecone numpy gradio sentence_transformers python-dotenv


2. Create a file named `config.env` in the project directory and add the following line to it:

PINECONE_API_KEY=your_pinecone_api_key


Replace `your_pinecone_api_key` with your actual Pinecone API key.

## Usage

1. Run the Python script:

python ai_semantic_search.py


2. Access the Gradio interface in your web browser.

3. Enter a query in the provided textbox and click "Submit".

4. The top three most similar sentences will be displayed in the output textbox.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.


