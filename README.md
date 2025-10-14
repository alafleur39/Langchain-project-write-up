# Langchain-project-write-up
# Tool / Skill Research Report

---

## Basic Information

| Field | Details |
|-------|----------|
| **Name** | _Andy Lafleur_ |
| **Project** | AI Knowledge Management Agent |
| **Role** |  Backend Developer |
| **Tool / Skill** |  Langchain|
| **Date** | 14 October 2025  |
| **Links / Sources** | [Official Docs](https://docs.langchain.com) · [GitHub Repo](https://github.com/langchain-ai/langchain) · [YouTube Tutorial](https://www.youtube.com/watch?v=1bUy-1hGZpI) |
---

## 1. Overview  

> _Example:_ 
> **LangChain**Langchain is a python framework used to build llm applications. We can use this to create our ai knowledge agent.

---

## 2. Core Features & Capabilities  

> _Example:_  
> - **Model:**We have the ability to use llm models such as openApi , Claude Anthropic.  
> - **Output Parsing / Structured Outputs:**. We can parse llm model text into python types this will be helpful for returning  
> - **Rag Components:** Document loaders, Text splitters, embeddings, retrievers, vector stores,.
> - **Integrations:** It works well with FastApi so we will be able to connect to our backend model we made with Langchain to our FastAPI layer.

---

## 3. Role in Our Project    
>LangChain will be the main framework we will be utilizing to create our Agentic ai model
> LangChain allows us to build an AI pipeline Orchestration 
> LangChain applications have Memory and can save the context of conversations for chatbots


---

## 4. Installation / Setup Guide  
> first go into vs code terminal or any ide terminal and setup a virtual environment
.```bash
python3 -m venv venv
source venv/bin/activate
>  Install the dependencies
> ```bash
> pip install fastapi uvicorn
pip install langchain langchain-community langchain-openai
pip install chromadb tiktoken pydantic python-dotenv
pip install pypdf
>
