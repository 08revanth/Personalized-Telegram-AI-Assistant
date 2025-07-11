# 🤖 AI Workflows with LangChain, Pinecone, and n8n

This repository showcases three AI automation projects built using **n8n**, **LangChain**, **OpenAI**, and **Pinecone**. These workflows demonstrate real-world use cases in conversational AI, RAG (Retrieval-Augmented Generation), and vector database integration.

## 📁 Project Structure

- [`/My_workflow.json`](./My_workflow.json): Telegram-based AI assistant with memory and context handling.
- [`/28+goldsmith_rag_app.json`](./28+goldsmith_rag_app.json): RAG chatbot for a goldsmith business with customer data collection.
- [`/27+Goldsmith_to_Pinecone.json`](./27+Goldsmith_to_Pinecone.json): Google Drive to Pinecone vector pipeline for automated document indexing.

## 🔸 Project 1: Personalized Telegram AI Assistant

**File:** `My_workflow.json`  
**Description:**  
A Telegram-integrated AI assistant that uses n8n and LangChain to respond intelligently to user messages. It supports text, voice, and image routing, performs user validation, and stores long-term memories in Google Docs for personalized responses.

**Key Features:**
- User identity validation via Telegram API
- Message type detection and routing
- Conversational memory using LangChain + Google Docs
- Error handling and fallback flows

**Tech Stack:**  
`n8n`, `LangChain`, `OpenAI`, `Telegram API`, `Google Docs`


## 🔸 Project 2: Goldsmith RAG Chatbot Application 💍

**File:** `28+goldsmith_rag_app.json`  
**Description:**  
A Retrieval-Augmented Generation (RAG) chatbot for a jewelry business ("Gold Digger"). It answers user queries using Pinecone vector search and stores user data (leads) like name, email, and interests in Google Sheets.

**Key Features:**
- LLM-powered assistant using LangChain Agent
- Domain-specific QA using Pinecone Vector Store
- Dynamic context memory buffer
- Automated lead capture to Google Sheets

**Tech Stack:**  
`n8n`, `LangChain`, `OpenAI GPT-4o`, `Pinecone`, `Google Sheets`

## 🔸 Project 3: Goldsmith → Pinecone Vector Ingestion

**File:** `27+Goldsmith_to_Pinecone.json`  
**Description:**  
An automated data pipeline that watches a Google Drive folder for new files, processes them into vector embeddings using OpenAI, and uploads them to Pinecone for future RAG applications.

**Key Features:**
- Google Drive file monitoring
- Automatic document loading & chunking
- OpenAI embeddings generation
- Vector storage to Pinecone in Q&A namespace

**Tech Stack:**  
`n8n`, `OpenAI Embeddings`, `Pinecone`, `Google Drive`, `LangChain`


## 🚀 How to Use

> **Prerequisites:**
> - [n8n](https://n8n.io/) installed locally or in the cloud
> - OpenAI API Key
> - Pinecone account & index
> - Google APIs setup (Sheets, Drive)
> - Telegram Bot token (for Project 1)

1. Import the desired `.json` file into your n8n instance.
2. Configure credentials (OpenAI, Google, Pinecone, Telegram).
3. Activate the workflow and test via the respective trigger (Telegram message, file upload, etc.).


## 🧠 Skills Demonstrated

- LangChain Agent & Tool usage
- Retrieval-Augmented Generation (RAG)
- Vector database integration (Pinecone)
- Real-time workflow automation
- Multi-modal input handling
- Low-code orchestration with n8n

## 📬 Contact

Created by **Revanth**  
Feel free to connect or collaborate!  
📧 [revanthmalagi@gmail.com]  
🌐 [https://www.linkedin.com/in/revanth-malagi/]

