# Semantic Search Application

## Overview
This repository hosts the code for a semantic search application that integrates Elasticsearch with the Sentence Transformers library to provide advanced search capabilities. It enables users to conduct searches based on semantic similarity, enhancing the relevance of search results by understanding the nuances in the context and meaning of queries.

## Features
- **Semantic Search**: Leverages BERT-based vector embeddings for semantic analysis of text data, allowing for more nuanced search results beyond mere keyword matching.
- **Streamlit Interface**: Offers a user-friendly web interface built with Streamlit, facilitating easy interaction with the search system.
- **Elasticsearch Backend**: Utilizes Elasticsearch for robust storage, indexing, and swift retrieval of data, supporting efficient semantic search operations.

## Installation

### Prerequisites
- Python 3.6 or later
- Elasticsearch 7.x or newer
- Access to an Elasticsearch cluster configured for HTTPS connections

### Setup
1. **Clone the Repository:**
```bash
git clone https://github.com/ingindIsrael/definitionDrawer.git
cd definitionDrawer
```

2. **Install Dependencies:**
```bash
pip install -r requirements.txt
```

3. **Configure Elasticsearch Connection:**
Ensure the script's Elasticsearch connection details accurately reflect your Elasticsearch instance's configuration.

### Running the Application
Execute the following command in your terminal to start the web application:
```bash
streamlit run app.py
```
Access the application by navigating to the Streamlit-provided URL in your web browser.
