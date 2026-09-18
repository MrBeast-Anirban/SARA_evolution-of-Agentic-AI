<b><i>April 2025</i></b>

# SARA: Agentic AI as an Alternative to Microservices for Intelligent Automation

## 🧠 Overview
**SARA (Scalable Agentic Reasoning Architecture)** is a modular, multi-agent system designed to autonomously process, route, and execute complex user tasks. Unlike traditional microservices, SARA leverages intelligent, context-aware agents that reason, adapt, and collaborate to deliver high-level automation across domains such as finance, cloud services, lifestyle, and more.

This project presents a comparative study between Agentic AI and traditional microservices for intelligent task automation and cloud orchestration.

---

## 📚 Table of Contents
- [Overview](#-overview)
- [Architecture](#-architecture)
- [Key Features](#-key-features)
- [Comparison with Microservices](#-comparison-with-microservices)
- [Methodology](#-methodology)
- [Results & Evaluation](#-results--evaluation)
- [Tech Stack](#-tech-stack)
- [Future Enhancements](#-future-enhancements)
- [Authors](#-authors)

---

## 🏗️ Architecture

### Agentic AI Framework (SARA)
SARA consists of a layered, cognitive pipeline of agents:
1. **Client Interface Agent**
2. **Authentication & Data Agent**
3. **Load Balancer Agent**
4. **Dispatcher Agent (Cognitive Router)**
5. **NLP & Prompt Interpreter**
6. **Main Category Agents**
7. **Subcategory Specialist Agents**
8. *(Optional)* **Memory Agent** for personalization

### Microservices Architecture (Baseline)
A parallel system built with:
- API Gateway
- Load Balancer
- Task Dispatcher
- Containerized Microservices
- Static response aggregator

---

## 🔑 Key Features
- **Cognitive Routing**: Semantic-based dispatcher routes requests to appropriate agents.
- **Adaptive Task Decomposition**: Breaks complex goals into manageable subtasks.
- **Plug-and-Play Agents**: Easily extensible with new roles/goals.
- **Memory & Personalization**: Optional long-term memory layer using FAISS or ChromaDB.
- **Secure & Parallel Execution**: TLS, OAuth2, JWT, and parallel task processing via CrewAI.

---

## ⚖️ Comparison with Microservices

| Feature                    | SARA (Agentic AI)                    | Traditional Microservices          |
|----------------------------|--------------------------------------|-----------------------------------|
| Routing                    | Semantic, cognitive-based            | Predefined request-based          |
| Flexibility                | High (goal + context-driven)         | Low (API-specific functions)      |
| Personalization            | Memory-enabled                       | Stateless                         |
| Extensibility              | Easy agent addition                  | Full-stack microservice changes   |
| Learning Capability        | Feedback-driven, adaptive            | Manual tuning only                |
| Best Use Case              | Complex, ambiguous, multi-domain     | Repetitive, high-throughput tasks |

---

## 🧪 Methodology
- **NLP Layer**: Parses user input using SentenceTransformers and OpenAI GPT.
- **Agent Hierarchy**:
  - Task Masters manage categories
  - Worker Agents execute fine-grained functions
- **Tools & APIs**: Integrated with OpenWeather, NewsAPI, SerpAPI, Google Cloud, CrewAI, LangChain.

---

## 📊 Results & Evaluation
- ✅ Better user intent understanding via semantic matching
- ✅ Dynamic response generation across multi-domain queries
- ✅ Faster development of new features through agent modularity
- ✅ Strong user feedback on naturalness, personalization, and UX

---

## 🧰 Tech Stack
- **Programming**: Python
- **Frameworks**: CrewAI, LangChain
- **APIs**: OpenAI, Google Cloud SDK, NewsAPI, OpenWeather, SerpAPI
- **Storage & Memory**: ChromaDB, FAISS
- **LLMs**: OpenAI GPT-3.5-Turbo

---

## 🚀 Future Enhancements
- Autonomous agent spawning via meta-prompting
- Real-time feedback loops for agent learning
- Memory-enhanced personalization across sessions
- Federated deployment of agents at the edge
- LLM-agnostic backend with support for Claude, Gemini, etc.

---

## 👨‍💻 Authors
- **Ankit Kumar Sharma** (M23CSA006)  
- **Sireejaa Uppal** (M23CSE023)  
- **Rudra Dutta** (D23CSA002)  
- **Anirban Maitra** (M23CSA005)  

> Department of Computer Science and Engineering  
> Project Year: 2025

---

## 📜 License
This project is part of an academic research submission and is intended for educational use only. Contact the authors for any collaboration or reuse queries.

