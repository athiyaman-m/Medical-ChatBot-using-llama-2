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

# Description
This project is a **Medical ChatBot** built using the **Llama-2** model. The primary goal of this chatbot is to provide accurate and relevant medical information to users based on their queries.

The **architecture** of the project is divided into two main parts: the **backend** and the **frontend**.

**Backend:**
1. **Data Ingestion:** The backend starts with ingesting data from a medical book in PDF format.
2. **Data Extraction:** The data from the PDF is then extracted and processed.
3. **Text Chunking:** The extracted data is broken down into smaller chunks or parts. These chunks are then fed into the model.
4. **Embedding:** Each chunk of text is converted into a vector representation, also known as embedding.
5. **Semantic Index Building:** A semantic index is built to connect these vectors, which aids in understanding the context and meaning of the text chunks.
6. **Knowledge Base:** The embeddings are stored in a knowledge base using Pinecone, a vector database.

**Frontend:**
1. **User Query Processing:** When a user asks a question, it is converted into a query embedding.
2. **Knowledge Base Lookup:** This query embedding is used to search the knowledge base for the most relevant information.
3. **LLM Model Processing:** The ranked results from the knowledge base are then passed through the LLM (Llama-2) model.
4. **User Answer Generation:** Finally, the model generates an answer to the user's question based on the information it has processed.

The **tech stack** used for this project includes:
1. **Python:** The primary programming language used for developing the chatbot.
2. **Langchain:** A framework used for building the chatbot.
3. **Flask, HTML, CSS:** These technologies are used for building the frontend or web application of the chatbot.
4. **Meta Llama-2:** The language model used for processing and generating responses to user queries.
5. **Pinecone:** A vector database used for storing the text embeddings.

In summary, this Medical ChatBot project leverages advanced NLP techniques and a robust tech stack to provide users with accurate medical information based on their queries. It represents a significant step forward in the field of AI-driven healthcare solutions.

# Output
![Screenshot (234)](https://github.com/athiyaman-m/Medical-ChatBot-using-llama-2/assets/116479721/405e8dc2-1089-4426-bde1-e6e2c835a643)



