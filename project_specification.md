project_specification.md
# Initial Group Project Specification
Local AI-Powered Decision Support System

Initial Group Project Specification

Course: Agentic AI / Decision Support Systems

Project Duration: 9 Weeks

Group Members: Muhammad Tahir, Lesley Muzavazi, and Ndongesit Bassey

Date: 2026-02-22

1. Project Title
Local AI-Powered Decision Support System for Small Business Operations Management

2. Project Overview
This project aims to design and implement a local, agentic Large Language Model (LLM)-based decision support system that assists small business owners and managers in making informed operational decisions.
The system will operate fully offline or in a privacy-preserving local environment and will integrate structured business data (sales, inventory, expenses) with unstructured documents (policies, notes, reports). Using retrieval, reasoning, and tool execution, the assistant will provide recommendations on inventory planning, cost optimization, and performance evaluation.
The project emphasizes transparency, interpretability, and practical usability.

3. Problem Statement
Small businesses often struggle to analyze operational data effectively due to limited technical expertise and lack of access to advanced analytics tools. Decisions regarding inventory, pricing, and budgeting are frequently based on intuition rather than data.
Existing AI tools are typically cloud-based, expensive, and raise privacy concerns.
There is a need for a local, intelligent, and explainable decision-support system that can:
•	Analyze internal business data
•	Retrieve relevant historical information
•	Reason through multiple options
•	Provide justified recommendations

4. Project Objectives
The main objectives are:
1.	Design a local LLM-powered agent capable of structured reasoning.
2.	Integrate retrieval mechanisms over business datasets and documents.
3.	Implement tool use for basic analytics (forecasting, summaries, comparisons).
4.	Provide explainable recommendations with supporting evidence.
5.	Evaluate system performance and usability.

5. Scope of the Project
Included
•	Local deployment of an open-source LLM.
•	Retrieval-Augmented Generation (RAG) over internal datasets.
•	Decision-support for:
o	Inventory management
o	Cost analysis
o	Sales performance
•	Simple user interface (CLI or web-based).
•	Logging and evaluation of agent decisions.
Excluded
•	Real-time external data integration.
•	Large-scale enterprise deployment.
•	Fully autonomous financial execution.

6. System Architecture (Proposed)
The system will consist of the following components:
1.	User Interface
o	Web or terminal interface for queries.
2.	LLM Core
o	Open-source model (e.g., LLaMA/Mistral-based).
3.	Retrieval Module
o	Vector database for document storage.
o	Embedding model for semantic search.
4.	Tool Layer
o	Python-based analytics tools.
o	CSV/Excel processors.
5.	Memory Module
o	Short-term and session-based memory.
6.	Controller / Agent Loop
o	Planning → Retrieval → Tool Use → Reasoning → Response.

7. Data Sources
•	Sample business datasets (CSV/Excel).
•	Simulated or anonymized transaction records.
•	Policy documents and reports.
•	Instructor-provided datasets (if available).

8. Technologies and Tools
•	Programming Language: Python
•	LLM Framework: LangChain / LlamaIndex (or similar)
•	Models: Mistral / LLaMA-based open-source models
•	Vector DB: FAISS / Chroma
•	Interface: Streamlit / Flask / CLI
•	Environment: Local machine or university server

9. Project Timeline (9 Weeks)
Week	Activity
1	Requirements analysis & final specification
2	Data preparation
3	Model setup
4	Retrieval system
5	Tool integration
6	Agent loop implementation
7	Interface development
8	Testing & evaluation
9	Documentation & presentation

10. Evaluation Criteria
The system will be evaluated based on:
•	Accuracy of recommendations
•	Quality of reasoning
•	System reliability
•	Usability
•	Performance
•	Documentation quality

11. Expected Deliverables
1.	Functional local AI system.
2.	Source code repository.
3.	Technical documentation.
4.	User manual.
5.	Final presentation.
6.	Evaluation report.

12. Risks and Mitigation
Risk	Impact	Mitigation
Limited hardware	Performance	Model optimization
Data quality	Accuracy	Data cleaning
Over-complexity	Delay	Scope control
Integration issues	Bugs	Modular design

13. Ethical and Legal Considerations
•	Data anonymization.
•	Local data storage.
•	Transparency in AI decisions.
•	Avoidance of biased recommendations.

14. Success Criteria
The project will be considered successful if:
•	The system runs locally without cloud dependency.
•	It produces consistent, explainable recommendations.
•	Users can effectively use it for decision-making.
•	All planned deliverables are completed on time.

