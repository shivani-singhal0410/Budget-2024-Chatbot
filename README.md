# Chatbot to answer queries based on uploaded PDF file
- This chatbot has been designed to answer questions based on uploaded pdf file. In this usecase, we have uploaded Budget 2024 speech pdf.
- The user can upload one or multiple pdf files. On click of "Submit and Process" button, the text is splitted and chunked to be saved as vector embeddings in a local file.
- The application uses Google Generative AI Embedding model to create vector embeddings for pdf text.
- The vector embeddings are stored using FAISS(Facebook AI Similarity Search) and saved as a local file.
- The Gemini-Pro model is used to answer the questions based on pdf file.
- The frontend has been designed using Streamlit.

##Screenshots for the app:

1. Initial Screen:
   ![image](https://github.com/user-attachments/assets/fffb6e99-452a-4489-8dd4-9e1cca526796)

   
 2. Upload PDF File and process it
    ![image](https://github.com/user-attachments/assets/fc96be0d-90d9-4e0d-a15d-46da97800e9d)


3. Get your queries answered by asking questions:
   ![image](https://github.com/user-attachments/assets/d7bdcd67-13c0-40ba-b174-881750df5ca0)
