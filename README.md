# Customer-Support-Multi-Ai-Agent-System
Elias AI is an intelligent Customer Support Agent built using LangChain, LangGraph, and Groq LLM, capable of understanding, categorizing, and responding to customer queries with semantic reasoning. It handles technical, billing, and general support, while escalating negative queries to a human agent


# Project Overview

# Elias AI is an Agentic AI-powered Customer Support System built using LangGraph, LangChain, and Groq LLMs.

The system automatically:

Classifies customer queries

Detects sentiment

Routes queries to the correct support handler

Generates AI responses

Escalates negative queries to human agents

It demonstrates how AI agents and workflow graphs can automate real-world customer support systems.


# System Architecture
<img width="1536" height="1024" alt="system" src="https://github.com/user-attachments/assets/9f31498f-0ff2-46d7-bb03-866fa092bfc8" />


# Workflow Explanation

1️⃣ User Query

Customer sends a support request.

2️⃣ Categorize Query

The AI classifies the query into:

Technical

Billing

General

3️⃣ Sentiment Analysis

The model analyzes the tone of the message.

4️⃣ Routing Logic

| Condition          | Action                    |
| ------------------ | ------------------------- |
| Technical Query    | Technical Support Handler |
| Billing Query      | Billing Support Handler   |
| General Query      | General Support Handler   |
| Negative Sentiment | Escalate to Human         |


# Key Features
# AI Query Classification

Automatically categorizes user queries into:

Technical Support

Billing Support

General Queries


# Sentiment Analysis

# The system detects the emotional tone of a message:

Positive

Neutral

Negative


# Intelligent Routing

Using LangGraph, queries are dynamically routed to the appropriate handler node.


# Automated Response Generation

Responses are generated using Groq's LLaMA-3.3-70B model.


# Escalation to Human Agent

If the system detects negative sentiment, the request is automatically escalated.


# Interactive Chat Interface

The project includes a clean chat UI built with Gradio.


# AI Workflow Graph
<img width="2823" height="720" alt="mermaid-diagram" src="https://github.com/user-attachments/assets/0b9f394f-d6b1-4d10-96db-43ea1c885785" />


# Tech Stack
# AI Models

LLaMA-3.3-70B (Groq)

# AI Frameworks

LangChain

LangGraph

# Backend

Python

TypedDict State Management

# Frontend

Gradio Chat Interface

# Visualization

Mermaid Diagrams

LangGraph Graph Visualization


# Install dependencies

pip install langchain

pip install langchain_core

pip install langchain_groq

pip install langchain_community

pip install langgraph

pip install gradio

pip install ipython


# Example Query

User:
My internet connection is very slow.

AI Output:
Category: Technical
Sentiment: Neutral

Response:
It seems you're experiencing slow internet speed.
Please try restarting your router and checking network cables.


# Use Cases

# This project demonstrates practical AI applications in:

🏢 Customer Support Automation

📞 Call Center AI Assistants

💻 Technical Support Bots

💳 Billing Support Systems

🤖 AI Agent Workflow Systems


# Future Improvements

# Potential enhancements:

Retrieval-Augmented Generation (RAG)

Multi-language support

Voice-based AI agent

CRM integrations

Ticket management system

Conversation memory

Analytics dashboard
