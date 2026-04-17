
Proposed Solution: AI-Powered Fraud Detection System
The proposed solution is a multi-agent AI-powered Fraud Detection System built using Lang Flow, IBM watsonx.ai, and Granite Models to detect and prevent fraudulent financial transactions in real time. The system addresses challenges in identifying suspicious payment activities, reducing financial risks, and improving trust in digital payment systems through an intelligent and modular architecture.
At its core, the solution leverages a Retrieval-Augmented Generation (RAG) pipeline combined with rule-based and machine learning techniques to analyze transaction data. Historical transaction datasets (such as Pay Sim or banking datasets) are embedded and stored in a vector database, enabling the system to identify patterns and detect anomalies. Granite models are used to interpret transaction behavior, classify fraud risk, and generate explainable outputs.
The system consists of four key agents:
Transaction Analysis Agent-Processes raw transaction data such as:
Transaction type (TRANSFER, CASH_OUT, etc.) ,Amount ,Sender and receiver balances
Fraud Detection Agent-Applies rules and machine learning models Detects suspicious patterns like: 
Unusually high transaction amounts ,Sudden balance drops ,Zero balance after transfer
Risk Scoring Agent-Assigns a fraud probability score Categorizes transactions into: High Risk ,Medium Risk,Low Risk



