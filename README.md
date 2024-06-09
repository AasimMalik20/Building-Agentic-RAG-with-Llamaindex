# 📚 Building Agentic RAG with Llamaindex 🦙

Welcome to the Building Agentic RAG with Llamaindex project! This repository is designed to help you create an advanced Retrieval-Augmented Generation (RAG) system that can dynamically interact with a variety of data sources and tools, leveraging the powerful Llamaindex framework. By combining retrieval-based methods with generative models, this system aims to provide accurate, context-aware responses, while continuously learning and adapting to new information.
## 🗂️ Contents

### 🔍 Router Query Engine

A Router Query Engine is a component that enables efficient querying of the knowledge graph or database. It acts as a gateway between the agent's reasoning loop and the underlying knowledge storage. The router query engine receives queries from the agent, optimizes them, and executes them against the knowledge graph, returning relevant results to the agent.
![Router Engine](https://github.com/AasimMalik20/Building-Agentic-RAG-with-Llamaindex/assets/68051104/1d363490-2004-41f2-ba02-f15c65f99ac9)

### 🛠️ Tool Calling

Tool Calling refers to the ability of the agent to invoke external tools, services, or APIs to perform specific tasks or retrieve information. This allows the agent to leverage external capabilities, such as language translation, entity disambiguation, or question answering, to augment its internal reasoning capabilities. The agent can call these tools through APIs, webhooks, or other interfaces.
![Tool Calling](https://github.com/AasimMalik20/Building-Agentic-RAG-with-Llamaindex/assets/68051104/e7e1faa8-883b-49ba-ae3a-166c7659df8f)

### 🔄 Building an Agent Reasoning Loop

An Agent Reasoning Loop is the core decision-making process of an intelligent agent. It involves the agent's iterative cycle of perception, reasoning, and action. The loop consists of:
* 👀 **Perception**: The agent observes its environment and updates its beliefs.
* 🧠 **Reasoning**: The agent reasons about the observed data, using its knowledge and rules to draw conclusions.
* 🚀 **Action**: The agent takes an action based on its reasoning, which may involve querying external tools or updating its internal state.
The reasoning loop enables the agent to continuously learn, adapt, and respond to its environment.
![Full Agent Reasoning Loop](https://github.com/AasimMalik20/Building-Agentic-RAG-with-Llamaindex/assets/68051104/fcad448f-e095-4f75-97fb-7bbd6f73c0eb)


### 📄 Building a Multi-Document Agent

A Multi-Document Agent is an intelligent agent that can process and reason about multiple documents or sources of information simultaneously. This allows the agent to integrate knowledge from diverse sources, identify relationships between them, and generate more comprehensive and accurate responses. The agent can also use this capability to identify inconsistencies or contradictions across documents.
![Three-documents Agent 1](https://github.com/AasimMalik20/Building-Agentic-RAG-with-Llamaindex/assets/68051104/3f3e6b11-bb46-4374-8d02-7d57ca1080ca)
![Three-documents Agent 2](https://github.com/AasimMalik20/Building-Agentic-RAG-with-Llamaindex/assets/68051104/e73a5c88-148a-45c0-b356-57572855d1f1)
![Eleven-documents Agent 1](https://github.com/AasimMalik20/Building-Agentic-RAG-with-Llamaindex/assets/68051104/c0f860dc-30e6-4b1a-b37e-a70bc01ee77b)
![Eleven-documents Agent 2](https://github.com/AasimMalik20/Building-Agentic-RAG-with-Llamaindex/assets/68051104/9cd1cb04-9dde-48a0-94e6-8f1ca6c7f98e)

## 🙏 Acknowledgements

This project is based on the course [Building Agentic RAG with Llamaindex](https://learn.deeplearning.ai/courses/building-agentic-rag-with-llamaindex/lesson/1/introduction) by DeepLearning.AI. Special thanks to the course creators and contributors for their valuable insights and guidance.

## 👥 Contributors

- **Instructor**: Jerry Liu
- **Special Thanks**: Logan Markewich - Llamaindex, Andrei Fajardo - Llamaindex, Diala Ezzeddine - DeepLearning.AI
