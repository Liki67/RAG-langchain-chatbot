**
RAG LangChain Chatbot**

This project implements a chatbot using LangChain with a Retrieval-Augmented Generation (RAG) architecture powered by Gemini (Google Generative AI). It allows users to ask questions about a given dataset and receive accurate, context-aware responses.

Built with:
	•	LangChain 🦜⛓️
	•	Google Generative AI (Gemini) 🔮
	•	Google Colab 💻
	•	Streamlit (optional frontend) 🌐

⸻

🚀 Features
	•	RAG (Retrieval-Augmented Generation) for grounded responses
	•	Chunked document ingestion using LangChain DocumentLoaders
	•	Custom embedding and vector store with FAISS
	•	Conversational memory support (via ConversationBufferMemory)
	•	Integration with Gemini Pro (via langchain-google-genai)
	•	Streamlit chatbot interface (optional)

<img width="1361" alt="Screenshot 2025-05-20 at 2 28 54 PM" src="https://github.com/user-attachments/assets/9a668cc0-3a7e-4067-828f-7d02d74d0fc6" />

⸻

📁 Folder Structure
	•	RAG_langchain_chatbot.ipynb — main Colab notebook (step-by-step implementation)
	•	/data — contains the input document (PDF, TXT, etc.)
	•	README.md — project documentation

⸻

📦 Installation

To run locally:
	1.	Clone the repository:
    git clone https://github.com/Liki67/RAG-langchain-chatbot.git
    cd RAG-langchain-chatbot
  2.	Set up a virtual environment (recommended):
    python -m venv venv
    source venv/bin/activate  # or venv\Scripts\activate on Windows
  3.	Install the required packages:
    pip install -r requirements.txt
    
