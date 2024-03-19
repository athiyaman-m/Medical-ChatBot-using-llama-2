# Medical-ChatBot-using-llama-2

Project - Medical ChatBot

# Architecture : 

Backend :
1) Data Ingestion : Medical book (Pdf file)
2) Extract data
3) Create different text chunks (break down big content into small chunks(parts) for to feed into model)
4) Embedding - vector
5) Build semantic index - (Connecting vector)
6) Knowledge base - (pinecone, vector store)
Frontend :
User questions -> Query embedding -> Knowledge base
Knowledge base -> Ranked result -> LLM model (llam2) -> user answer


# Tech stacks:
1) Language - Python
2) Framework - Langchain or llama index
3) Frontend/webapp - Flask
4) LLM - meta llama 2
5) Vector DB - pinecone.

# Implementation

Step 1 : Create virtual Environement 
Anaconda cmd -> conda create -n machatbot python=3.8 -y

step 2 : Activate environment

step 3 : Requirements added.