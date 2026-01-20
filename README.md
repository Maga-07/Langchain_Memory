# LangChain Memory Implementation

This project demonstrates how memory works in LangChain using free and open-source models.  
It is built to run completely on Google Colab, without using OpenAI or any paid APIs.

The goal of this repository is to help beginners clearly understand how different memory types store and use conversation context in LangChain.

---

## What this project is about

By default, LLMs are stateless — they don’t remember previous messages.  
LangChain provides different memory mechanisms that allow chatbots to remember past conversations.

This project shows:
- How memory works
- When to use which memory
- Simple, working examples for each memory type

---

## Memory Types Implemented

- ConversationBufferMemory  
- ConversationBufferWindowMemory  
- ConversationSummaryMemory  
- ConversationSummaryBufferMemory  
- VectorStoreRetrieverMemory (using FAISS)  
- CombinedMemory  

Each memory type is implemented with a small example for easy understanding.

---

## Tech Stack

- Python  
- LangChain  
- HuggingFace Transformers  
- FAISS  
- Google Colab  

All models used are **free and open-source**.

---


