# Simple_Search_Engine

SimpleSearch is a Python-based PDF document search engine that allows users to search for specific keywords within PDF files and retrieve relevant pages containing those keywords. This project aims to provide a simple and efficient solution for searching through PDF documents without the need for complex search algorithms.

## Features
- **Keyword Search:** Users can input keywords to search for within PDF documents.
- **PDF Parsing:** The search engine parses PDF files to extract text content for indexing.
- **Keyword Indexing:** Documents are indexed based on keywords, allowing for fast retrieval of relevant pages.
- **TF-IDF Vectorization:** The search engine utilizes TF-IDF vectorization for efficient keyword matching and ranking.
- **Stemming:** Keywords are stemmed to their root form for improved search accuracy.
- 
## How it Works
1. **Indexing:** PDF documents are indexed based on keywords extracted from their text content.
2. **Search:** Users input keywords to search for within the indexed documents.
3. **Retrieval:** Relevant pages containing the searched keywords are retrieved and displayed to the user.

## Usage
1. **Indexing Documents:** Use the `index_pdf()` method to index PDF documents.
2. **Searching:** Use the `search()` method to search for keywords within the indexed documents.

   
