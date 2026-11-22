# 🤖 Google ADK AI Agent Projects

A collection of AI agent projects built using **Google Agent Development Kit (ADK)**, **Gemini**, **Google Cloud**, and modern GenAI technologies.

This repository demonstrates practical implementations of **Agentic AI, Retrieval-Augmented Generation (RAG), semantic search, MCP, BigQuery integration, tool calling, and cloud deployment**.

---

# 🚀 Projects

## ☕ 1. Google ADK RAG Coffee Assistant

An AI-powered Coffee Shop Assistant built using **Google Agent Development Kit (ADK)**, **Gemini**, **Streamlit**, **Cloud Run**, and **Cloud Firestore Vector Search**.

The agent provides grounded coffee recommendations by retrieving relevant menu information using semantic vector search.

### Features

- AI Barista powered by Gemini
- Google Agent Development Kit (ADK)
- Retrieval-Augmented Generation (RAG)
- Cloud Firestore Vector Search
- Semantic Search using Embeddings
- Tool Calling
- Streamlit Chat Interface
- Cloud Run Deployment
- Google Cloud IAM

### Architecture

```text
User
  ↓
Streamlit Web Interface
  ↓
Google ADK Agent
  ↓
Tool Calling (get_menu)
  ↓
Firestore Vector Search
  ↓
Relevant Menu Items
  ↓
Gemini
  ↓
Grounded Coffee Recommendation
```
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

2. BigQuery Data Strategy Agent

An AI-powered data analysis agent built using Google ADK, Gemini, Model Context Protocol (MCP), and BigQuery.
The agent connects an LLM to BigQuery through MCP tools, retrieves business data, analyzes the results, and provides business suggestions, strategies, and recommendations based on the available data.
Key Features
•	Google Agent Development Kit (ADK) 
•	Gemini 
•	Model Context Protocol (MCP) 
•	BigQuery Integration 
•	MCP Tool Calling 
•	Natural Language Data Analysis 
•	Business Data Retrieval 
•	AI-powered Strategy & Recommendations 
•	Google Cloud Run Deployment 
Architecture
User
  ↓
Google ADK Data Agent
  ↓
Gemini
  ↓
MCP Tool
  ↓
BigQuery
  ↓
Business Data
  ↓
Data Analysis
  ↓
Business Reasoning
  ↓
Strategy / Recommendation

google-adk-rag-coffee-assistant/
│
├── agent.py
├── app.py
├── menu.json
├── seed.py
├── requirements.txt
├── README.md
│
├── data-agent/
│   ├── agent.py
│   ├── __init__.py
│   └── requirements.txt
│
└── GOOGLE COFFEE BARISTA AGENT PROOF.pdf
🛠️ Technologies Used
Generative AI & Agentic AI
•	Google Agent Development Kit (ADK) 
•	Gemini 
•	Agentic AI 
•	Tool Calling 
•	Model Context Protocol (MCP) 
•	Retrieval-Augmented Generation (RAG) 
•	Prompt Engineering 
•	Semantic Search 
•	Embeddings 
Data & Cloud
•	Google BigQuery 
•	Cloud Firestore 
•	Firestore Vector Search 
•	Vertex AI 
•	Cloud Run 
•	Google Cloud IAM 
•	Google Cloud Build 
Development
•	Python 
•	Streamlit 
•	Git 
•	GitHub 
________________________________________
🧠 Skills Demonstrated
•	Building AI agents using Google ADK 
•	Designing agent-to-tool workflows 
•	Model Context Protocol (MCP) 
•	Tool calling and external data access 
•	Retrieval-Augmented Generation (RAG) 
•	Semantic vector search 
•	Embedding-based retrieval 
•	Connecting LLMs with structured business data 
•	AI-powered data analysis 
•	Business reasoning and recommendation generation 
•	Cloud-native AI application development 
•	Deploying AI agents on Google Cloud Run 
•	IAM and cloud security principles 
________________________________________

Cloud Architecture

The projects demonstrate different patterns for connecting LLMs with external knowledge and data:

                    ┌─────────────────────┐
                    │        User         │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   Google ADK Agent  │
                    └──────────┬──────────┘
                               │
                         ┌─────┴─────┐
                         │   Gemini  │
                         └─────┬─────┘
                               │
                ┌──────────────┴──────────────┐
                │                             │
                ▼                             ▼
       ┌─────────────────┐           ┌─────────────────┐
       │   RAG / Vector  │           │   MCP / Tools   │
       │     Search      │           │                 │
       └────────┬────────┘           └────────┬────────┘
                │                             │
                ▼                             ▼
       ┌─────────────────┐           ┌─────────────────┐
       │    Firestore    │           │    BigQuery     │
       │ Vector Search   │           │                 │
       └─────────────────┘           └─────────────────┘
__

______________________________________
🔮 Future Improvements
•	Multi-agent architecture 
•	Agent orchestration 
•	Persistent conversation memory 
•	Agent observability 
•	Cloud Logging & Monitoring 
•	Agent evaluation and tracing 
•	Production-grade guardrails 
•	User authentication 
•	CI/CD with GitHub Actions 
•	Additional enterprise data sources 
________________________________________
Author
Ayan Mitra

