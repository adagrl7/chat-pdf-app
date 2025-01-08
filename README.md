Overview
"Ask Your PDF" is a Streamlit-based application that allows users to interact with the content of any uploaded PDF by asking questions about it. Using the power of LangChain and OpenAI, this project enables semantic search and question answering on PDF documents, providing quick, accurate, and context-aware responses.

Features
PDF Upload: Upload any PDF file through a user-friendly Streamlit interface.
Text Extraction: Automatically extracts text content from the PDF for processing.
Text Splitting: Splits large PDF text into manageable chunks for efficient embedding and search.
Vector Search: Uses FAISS to create a knowledge base for similarity search on document chunks.
Question Answering: Leverages OpenAI's GPT-3.5 model to provide accurate answers to user questions based on the PDF's content.
Interactive Interface: Intuitive input field for users to ask their queries and get real-time responses.\

Technologies Used
Streamlit: For building the interactive web application.
PyPDF2: For extracting text from PDF documents.
LangChain: For text chunking, embedding generation, and question-answering chains.
FAISS: For efficient vector similarity search.
OpenAI GPT-3.5: As the LLM for natural language understanding and response generation.
