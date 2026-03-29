# 📈 Stock Analyst Agent: High-Signal Equity Research

A production-ready AI agent built with the **Google Agent Development Kit (ADK)** and deployed on **Google Cloud Run**. This agent acts as a Senior Equity Research Analyst, providing objective, data-driven briefings on global stocks.

## 🚀 Live Demo
[**Access the Agent UI here**](https://stock-market-analyst-115855631906.us-central1.run.app)

---

## 🧠 Agent Architecture
The agent is designed as a single-agent orchestrator using **Gemini 1.5 Flash**. It follows a strict "Hedge Fund Protocol" to ensure all outputs are professional, objective, and concise.

### Key Features
* **Real-time Analysis**: Processes ticker symbols to provide current price action and recent catalysts.
* **Strict Constraints**: Built-in guardrails to prevent financial advice (Buy/Sell/Hold) and price hallucinations.
* **Production-Ready**: Containerized with Docker and deployed to a serverless environment for global scaling.

---

## 🛠️ Technical Stack
* **Core Framework**: Google ADK (Agent Development Kit) v1.14.0
* **LLM**: Gemini 2.5 Flash (via Vertex AI)
* **Infrastructure**: Google Cloud Run (Serverless)
* **Deployment**: Artifact Registry & Cloud Build


