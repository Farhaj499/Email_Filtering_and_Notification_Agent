# Email Filtering and Notification Agent

This project implements an intelligent email management system designed to filter, categorize, summarize, and notify users about important emails. It uses a modular architecture with several interacting agents to achieve this.

## Architecture

The system is composed of the following agents:

*   **Email Ingestion Agent:** Connects to email servers via APIs, retrieves new emails, and pre-processes them (e.g., removing HTML tags, decoding special characters).
*   **Filtering & Classification Agent:** Classifies emails based on importance using machine learning models, filters spam/junk, and categorizes emails (e.g., work, personal, social).
*   **Summarization Agent:** Generates concise summaries of important emails using NLP techniques.
*   **Notification Agent:** Manages notifications based on user preferences, including channel selection (voice call, WhatsApp).

## Technology Stack:
*   **Programming Language:** Python
*   **NLP Libraries:** Transformers
*   **LLM Frameworks:** LangChain, LangGraph (for orchestrating agents, defining workflows, and managing LLM interactions)
*   **Large Language Model:** Google Gemini 1.5 Flash
*   **Email Libraries:** imaplib, email
*   **Notification Libraries/APIs:** Twilio (WhatsApp), Blandai
