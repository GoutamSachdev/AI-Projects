# 🚀 Multi-Agent AI Customer Support System

This project implements an AI-driven multi-agent system for customer support automation using **CrewAI**, **LangChain**, and **LLMs**. It leverages **CrewAI agents** to provide accurate, friendly, and real-time responses to customer inquiries using structured data (FAQs, CSV datasets) and web scraping.

## 📌 Features
- 🤖 **Multi-Agent Collaboration**: Three AI agents handle different aspects of customer support:
  - **IT Specialist Agent**: Resolves IT-related queries using structured CSV data.
  - **General IT Support Agent**: Answers common FAQs and provides troubleshooting guidance.
  - **Website Support Agent**: Scrapes and extracts verified details from the company website.
- 📊 **Data-Driven Responses**: Uses **Kaggle datasets**, JSON FAQs, and web content to ensure fact-based answers.
- 🌐 **Web Scraping for Real-Time Info**: Dynamically fetches data from the company's website to enhance support quality.
- 🏗 **Hierarchical CrewAI Process**: Organizes agents efficiently to optimize task execution.
- 🔥 **Powered by LLMs**: Uses **Groq AI models (DeepSeek & Qwen-2.5-32B)** for intelligent natural language processing.
- 🔎 **Context-Aware Search**: Integrates JSON and CSV search tools for accurate retrieval.

## 🛠️ Tech Stack
- **Python**
- **CrewAI**
- **LangChain**
- **Groq API (LLMs)**
- **Kaggle API**
- **JSON & CSV Data Processing**
- **Web Scraping**

## 📂 Folder Structure
