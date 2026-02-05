# Web Searching and Crawling Agent

## Description
This project implements a Retrieval-Augmented Generation (RAG) agent that searches the web, crawls content, and uses Google's Gemini LLM to answer user queries with up-to-date information.

## Features
- **Smart Search**: Rephrases user queries avoiding to optimize search results.
- **Web Crawling**: Fetches and cleans content from search results.
- **Vector Database**: Uses FAISS and HuggingFace embeddings for efficient context retrieval.
- **LLM Powered**: precise answers using Google Gemini 1.5 Pro and relevant web context.

## Setup
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Create a `.env` file with your API keys:
   ```env
   google_search_api_key=YOUR_KEY
   google_search_project_id=YOUR_ID
   google_gemini_api_key=YOUR_KEY
   ```

## Usage
Open and run the `main.ipynb` notebook to query the agent. change the `user_query` variable to ask different questions.
