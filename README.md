# AI-Document-Assistant-n8n-Automation
A modular, AI-powered workflow built on n8n that allows you to upload any document (PDF, text file, report, policy, contract, CV, etc.), extract its content, store it in a searchable vector memory, and chat with it using an AI agent.

# Overview

This project is a simple but powerful automation that turns n8n into a Document Question-Answering system.
You can upload any file or point to a file stored on Google Drive, and the workflow will:

Read and extract the text

Break the text into chunks

Create AI embeddings

Store everything in a vector memory

Let you ask questions or request summaries

Respond based on actual content from your document

The goal is to make document understanding easy, interactive, and reusable.


# What This Workflow Can Do

✔ Summarize long documents
✔ Allow you to “chat” with a file
✔ Extract key insights, dates, definitions, policies
✔ Rewrite or simplify content
✔ Analyze legal, technical, or academic documents
✔ Tailor content for job applications, reports, or reviews
✔ Support multiple document types (PDF, Markdown, text)

# Tech Stack

n8n Automation Platform

LangChain Nodes

OpenAI (GPT-4.1-mini or higher)

Google Drive API

Vector Store (in-memory RAG)

Document Loaders & Recursive Text Splitter


# How the Automation Works
1️. Trigger

A chat message or HTTP endpoint starts the workflow.

2️. Download Document

The workflow pulls the file from Google Drive using a File ID.

3️. Extract Text

Uses Extract from File to read PDF or text contents.

4️. Chunking + Embeddings

The document is split into smaller, meaningful pieces.
Each chunk is converted into an embedding using OpenAI.

5️. Vector Store

All chunks + embeddings are stored in a memory vector store.

6️.  AI Agent

The agent uses:

the vector store (retrieval)

a chat language model

short-term memory buffer

…to answer document-specific questions.



**Workflow Overview**

<img width="3836" height="2027" alt="Screenshot 2025-11-18 165922" src="https://github.com/user-attachments/assets/a34a2a0f-2222-41e5-afe6-4727aa78bc41" />



**AI Response Example**


<img width="3501" height="1486" alt="Screenshot 2025-11-18 165750" src="https://github.com/user-attachments/assets/295a69f2-1648-4628-9b7c-499f5d107030" />

<img width="3730" height="1861" alt="Screenshot 2025-11-18 165840" src="https://github.com/user-attachments/assets/85f0e7eb-16e5-4074-a12a-28fe89262876" />



# Example Use Cases

This project can be used for:

CV and job application optimization

Reading long policy or compliance documents

Extracting insights from technical manuals

Academic paper summarization

Contract explanation

Meeting preparation

Onboarding document review

Automating personal note analysis


# Why This Project Is Useful

It demonstrates real-world skills:

RAG (Retrieval-Augmented Generation)

AI automation

API integration

Workflow design

Document processing

Practical problem-solving

Perfect for showcasing AI engineering + automation experience.


**Author**

Obiora Emmanuel Ikechukwu
AI Automation • n8n Developer • Security & Data Enthusiast
GitHub: https://github.com/CrAzI-code
LinkedIn: https://www.linkedin.com/in/emmanuel-obiora-93116318b/
