# 📌 Intelligent RAG Chatbot Using n8n, Google Gemini & Supabase Vector DB
This repository contains my n8n workflow for building a complete Retrieval-Augmented Generation (RAG) chatbot using Google Gemini, Supabase, and vector search.
--
## Workflow Features

- Automatic Document Ingestion
Downloads files from Google Drive via n8n's “Download File” node.

- Text Splitting Pipeline
Uses Recursive Character Text Splitter to generate 1200+ optimized chunks.

- Embedding Generation
Creates dense vector embeddings using Google Gemini Embeddings Model.

- Vector Storage
Stores embeddings in Supabase Vector Store for semantic search.

- AI Agent Response System
When a user sends a message → retrieves relevant chunks → generates an answer via Google Gemini Chat Model.

- Real-Time Interaction
Chat trigger via Webhook → AI Agent → Vector Search → Response Generation.

-- 

<img width="1366" height="768" alt="Screenshot 2025-12-16 123544" src="https://github.com/user-attachments/assets/a3b2a1ff-70a0-4c6a-9b0f-456609b2a714" />

--

## 🛠️ Tech Stack

- n8n workflow automation

- Google Gemini (Embeddings + Chat Model)

- Supabase Vector Database

- Webhooks

- RAG (Retrieval-Augmented Generation)

--

## 📂 Use Cases

- Knowledge-base chatbot

- Document Q&A

- Customer support automation

- AI assistants for internal teams
