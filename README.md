# Agentic-RAG-with-LlamaIndex-OpenAI

This repository contains 4 Notebooks: 

## 1 Agentic RAG with LlamaIndex and OpenAI
This project implements an Agentic Retrieval-Augmented Generation (RAG) using LlamaIndex and OpenAI API to process and query information from a PDF document. The system is designed to have two query engines: summary_query_engine to summarize the document and qa_query_engine to answer specific questions. The Router Query Engine selects dynamically the best query engine based on user input.

## 2 Tool Calling with LlamaIndex and OpenAI
This project is aimed to explore Tool Calling, which helps select not only the best query engine but also arguments to pass through the function, for example a page number. 
Tool Calling adds a layer of query understanding on top of the RAG pipeline, enables users to ask complex queries and to receive more accurate answers.

## 3 Building an Agent Reasoning Loop with LlamaIndex and OpenAI
What if a user asks a complex question with multiple steps to be clarified? This project is aimed to implement complete Agent Reasoning Loop, which, instead of tool calling, is able to reason over tools and multiple steps.

## 4 Building a Multi-Document Agent with LlamaIndex and OpenAI
In this project we learn how to extend Agent to handle multiple documents and increasing complexity.

# References
This project is based on the excellent and inspiring course **"Building Agentic RAG with Llamaindex"** by **Deeplearning.AI** and is available at the following [link](https://learn.deeplearning.ai/courses/building-agentic-rag-with-llamaindex/).
Thank you to the team, developed this course!

