# Chatbot to answer queries based on uploaded PDF file
- This chatbot has been designed to answer questions based on uploaded pdf file. In this usecase, we have uploaded Budget 2024 speech pdf.
- The user can upload one or multiple pdf files. On click of "Dubmit and Process" button, the text is splitted and chunked to be saved as vector embeddings in a local file.
- The application uses Google Generative AI Embedding model to create vector embeddings for pdf text.
- The vector embeddings are stored using FAISS(Facebook AI Similarity Search) and saved as a local file.
- The Gemini-Pro model is used to answer the questions based on pdf file.
- The frontend has been designed using Streamlit.
