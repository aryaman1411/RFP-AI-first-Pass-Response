# RFP-AI-first-Pass-Response
Project Summary
This project involves building an AI-powered RFP (Request for Proposal) Assistant that leverages a Retrieval-Augmented Generation (RAG) system to efficiently retrieve and synthesize responses from a collection of RFP documents and their corresponding responses. The system is designed with a Flask backend and a React frontend, enabling users to query information from the RFP database and receive relevant responses.

The backend utilizes LlamaIndex, an advanced retrieval library, to perform hybrid search—combining both keyword-based (BM25) and vector-based search techniques. Alpha tuning is implemented to balance these search methods, optimizing relevance scores for different types of queries. The relevance score is calculated and displayed to users, providing insights into how well the retrieved information matches their query. Additionally, various metrics such as Hit Rate and Mean Reciprocal Rank (MRR) are used to evaluate and visualize the performance of the retrieval system.

This project demonstrates the integration of cutting-edge retrieval techniques with a user-friendly interface, making it a valuable tool for efficiently managing and querying large collections of RFP documents.
