# QuickRAG 📖 Multi-PDF Question-Answer Assistant
This application is a powerful, interactive tool that transforms your PDFs into an accessible knowledge base. Simply upload one or more PDFs, ask questions about their content, and receive quick, accurate, and easy-to-understand answers that are strictly derived from the provided documents. Built with a focus on precision, the application ensures clarity by explicitly stating when the requested information is not available in the documents.


### QuickRAG demonstrates the core principles of Retrieval-Augmented Generation (RAG) by:

- Extracting and chunking text from uploaded PDFs.
- Generating embeddings to encode the document context meaningfully.
- Storing embeddings in an in-memory vector store for fast retrieval.
- Leveraging a retrieval mechanism to provide accurate, context-specific responses to user queries.

## Tech used
- **FAISS:** Used as an in-memory vector store for fast, efficient similarity searches, making it perfect for retrieving relevant information from processed PDF content.
- **LangChain:** Provides seamless integration for document chunking, embedding generation, and chaining retrieval with LLM-based reasoning.
- **GPT-4o-mini:** Offers powerful language understanding and reasoning capabilities while being computationally efficient.


# Demo

https://github.com/user-attachments/assets/4e442642-c260-456c-884d-5806808cd728

