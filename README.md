# News Research Tool  

## Overview  
The **News Research Tool** is designed to streamline the process of extracting, indexing, and querying information from news articles. Leveraging **LangChain**, **OpenAI embeddings**, and **FAISS**, this tool allows users to fetch article content, process it into embeddings, and interact with the data through a user-friendly **Streamlit app**.  

## Features  
- Fetch article content from a list of URLs or uploaded text files containing URLs.  
- Process articles using LangChain's **UnstructuredURLLoader** for effective content extraction.  
- Generate embedding vectors with **OpenAI embeddings** and index them using **FAISS**, enabling swift and accurate information retrieval.  
- Ask questions via an **LLM (ChatGPT)** and receive context-rich answers along with source URLs.  
- Embedding vectors are stored locally in **pickle** format for easy reuse.  

## Installation  
1. Clone the repository to your local machine:  
   ```bash  
   git clone https://github.com/codebasics/langchain.git  
