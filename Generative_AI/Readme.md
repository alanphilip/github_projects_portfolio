Gemini AI Project 🚀

A collection of Python applications demonstrating the use of Google Gemini (Generative AI) models for text generation, chatbots, code assistance, role-play simulations, retrieval-augmented generation (RAG), semantic search, and text embeddings.

🧩 Applications Overview

1. Text Generation (text_gen_app.py)
    * Uses Gemini 2.5 Flash to generate text completions. 

2. Chat Applications (chat_bot.py)
   
   * General-purpose chatbot with helpful assistant persona. 

3. Code Assistant (code_assistant.py)

   Python study buddy that explains concepts with:
   * Concept overview 
   * Example code 
   * Detailed explanation

4. History Bot (history_bot.py)

   * Role-playing chatbot that answers as historical characters, grounded in facts.

5. Search Applications (rag_app.py)

   Retrieval-Augmented Generation (RAG) demo:
   * Embeds documents 
   * Retrieves best match 
   * Generates context-aware answers

6. Semantic Text Search (semantic_search.py) 

   * Semantic search engine using embeddings and cosine similarity.

7. Text Embedding Applications (text_embedding_app.py)

   * Generates embeddings for text using text-embedding-004.

🔑 Key Features 
    
    * Environment variable management with dotenv.
    * Secure API key handling.
    * Generative AI integration with Gemini models.
    * Embeddings & semantic search using cosine similarity.
    * Role-based assistants (chat, code, history).
    * RAG pipeline for context-aware answers.

✨ Future Enhancements 

   * Vector DB Integration: Replace linear search with Pinecone, FAISS, or Weaviate for scalable semantic search and RAG.

   * Streamlit or Flask UI: Add a web interface to interact with each module visually.

   * Session Memory for Chatbots: Implement conversational memory using Gemini's chat history or external storage.

   * Async Embedding Pipeline: Optimize embedding generation with asynchronous calls and caching.

   * Modular Logging & Error Handling: Centralize logs and exceptions for better debugging and monitoring.

   * Dockerization: Containerize the project for easy deployment across environments.

   * Unit Tests & CI/CD: Add Pytest coverage and GitHub Actions for automated testing and deployment.



🏆 Acknowledgments

    * Built with Google Generative AI (Gemini).


👤 Author

   * Alan Philip
   * Date of Last Revision: 22-Nov-2025