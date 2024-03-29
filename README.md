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
1) User questions -> Query embedding -> Knowledge base
2) Knowledge base -> Ranked result -> LLM model (llam2) -> user answer


# Tech stacks:
1) Language - Python
2) Framework - Langchain
3) Frontend/webapp - Flask, HTML, CSS
4) LLM - meta llama 2
5) Vector DB - pinecone.
