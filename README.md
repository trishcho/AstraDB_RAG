# AstraDB_RAG


# Quickstart with RAGStack
This notebook provides a step-by-step guide to setting up a simple Retrieval-Augmented Generation (RAG) pipeline using RAGStack. 


![Screenshot 2024-08-29 at 9 48 10 PM](https://github.com/user-attachments/assets/ad577bef-305c-4e8f-99ab-49c4e3d0bfd3)


Overview
A RAG pipeline typically requires a vector store, an embedding model, and a Language Learning Model (LLM). In this tutorial, we utilize the following components:

Vector Store: Astra DB (Datastax)
Embedding Model: OpenAI
LLM: OpenAI
Orchestration: LangChain
Prerequisites
To get started, you'll need the following:

Astra DB Vector Store: Set up an Astra DB vector database.
OpenAI Account: Create an account to access OpenAI's API.
Astra DB Access Token: Generate a Database Administrator token within your Astra DB instance.
Astra DB Endpoint: Obtain your Astra DB endpoint in the format: https://<ASTRA_DB_ID>-<ASTRA_DB_REGION>.apps.astra.datastax.com.
For detailed instructions, see the Prerequisites section.
