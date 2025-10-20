# RAG-chat
Retrieval Augmented Generation based Chatbot

![thumbnail](https://github.com/user-attachments/assets/892b8df2-ebed-4069-a8ec-a1c0483f838d)

Oversimplified explanation : (Retrieval) Fetch the top N similar contexts via similarity search from the indexed PDF files -> concatanate those to the prompt (Prompt Augumentation) -> Pass it to the LLM -> which further generates response (Generation) like any LLM does.

- Streamlit for UI
- Ollama for text generation
- Chromadb for vector storage

