# Custom Question Answering with FAISS, HuggingFace, and RAG Evaluation
This project demonstrates how to build a custom question-answering (QA) system using FAISS for document retrieval, HuggingFace for embedding and language generation models, and the ROUGE metric for evaluating answer quality.

## Features
*  **Document Embedding and Vector Search:**  Use HuggingFaceEmbeddings to embed text documents and store them in FAISS for efficient similarity-based retrieval.
*  **Custom QA Chain:** Retrieve relevant documents using a retriever, and generate answers using a text generation model from HuggingFace.
*  **Evaluation:** Evaluate the performance of the system using ROUGE-L F1 score and retrieval precision on a subset of the SQuAD dataset.
