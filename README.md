# AgriPulse: Autonomous Climate-Resilient Advisory and Diagnostic Agent

1M1B AI for Sustainability Virtual Internship Project
Aligned with UN Sustainable Development Goals (SDGs):
- SDG 2: Zero Hunger
- SDG 12: Responsible Consumption and Production
- SDG 13: Climate Action

---

## Project Overview
In this project, I developed AgriPulse, an autonomous agent-driven advisory system built to protect smallholder farmer crop yields against unseasonal weather shocks, emerging diseases, and pest infestations.

I integrated Retrieval-Augmented Generation (RAG) with deterministic Agentic workflows to ground every recommendation in verified agricultural science. This approach eliminates typical LLM hallucinations and provides actionable advice that prevents the over-application of costly chemical inputs.

---

## Key Technologies Used
- LangChain and ChromaDB: Built a vector database to store and retrieve verified agronomic protocols and management strategies.
- Hugging Face Embeddings: Integrated all-MiniLM-L6-v2 to convert domain documents into vector embeddings for semantic retrieval.
- Agentic Architecture: Programmed an autonomous pipeline that evaluates incoming field telemetry (soil moisture, rainfall, humidity) alongside farmer observations.
- IBM AI Frameworks and Tooling: Applied concepts aligned with IBM Granite Foundation Models and spec-driven development practices from IBM BOB.

---

## How My Solution Works
1. Telemetry and Query Ingestion: I capture the farmer's observation along with simulated real-time soil and weather sensor data.
2. Context Retrieval: My system performs a vector similarity search across the agronomic knowledge base to fetch targeted, peer-reviewed mitigation guidance.
3. Agentic Advisory Generation: The agent structures the retrieved context into a clear advisory report detailing immediate crop triage, optimized chemical use, and long-term climate resilience steps.
