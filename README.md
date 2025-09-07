# Research Paper Summarizer with RAG (LangChain + Watsonx)
A Research Paper Summarizer powered by IBM Watsonx and ChromaDB, enabling users to upload PDFs and get concise summaries and answers to queries

## Overview
This project is a Retrieval-Augmented Generation (RAG) based application built with LangChain that helps users quickly understand research papers.

* Upload a PDF research paper
* The application automatically generates a concise summary
* Users can then ask questions about the paper (methods, results, key findings, etc.), and the assistant answers using the uploaded document

It combines:

* Watsonx LLM (for summarization and Q&A)
* Watsonx Embeddings (for semantic search in documents)
* Vector database - ChromaDB (for storing/retrieving document chunks)
* LangChain (for orchestration)
* Gradio (for user-friendly interface)

## Features
* Automatic summarization of uploaded research papers
* Ask follow-up questions about the paper using natural language
* Retrieval-Augmented Generation (RAG) ensures accurate, document-grounded answers
* Built with IBM Watsonx API for enterprise-grade 

## Future Improvements
* Add section-wise summaries (Abstract, Methods, Results)
* Support multiple documents at once
