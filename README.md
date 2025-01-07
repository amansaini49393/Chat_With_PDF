# Chat_With_PDF
A Streamlit web app that allows users to interact with PDF documents using Google Gemini AI. The app processes PDF files, extracts text, generates embeddings using LangChain, and answers user queries based on the contents of the uploaded PDFs.

🚀 Features:
	•	📄 Upload Multiple PDF Files
	•	📖 Text Extraction from PDFs using PyPDF2
	•	🧠 Google Gemini Integration for AI Responses
	•	📊 FAISS Vector Database for Efficient Document Searching
	•	🌐 Streamlit Web Interface

📦 Requirements:
	•	Python 3.7 or higher
	•	streamlit
	•	PyPDF2
	•	langchain
	•	google-generativeai
	•	python-dotenv
	•	faiss-cpu

Steps to Use the App:
	1.	Upload one or more PDF files using the sidebar uploader.
	2.	Ask a question related to the content of the PDF.
	3.	The app will process the PDFs and answer your question using Google Gemini AI.

📦 How It Works:
	1.	PDF Upload: The user uploads one or more PDF files.
	2.	Text Extraction: The content is extracted using PyPDF2.
	3.	Text Chunking: The text is split into smaller chunks using RecursiveCharacterTextSplitter.
	4.	Embedding Generation: Google Gemini’s embedding-001 model generates vector embeddings.
	5.	FAISS Storage: The embeddings are stored in a FAISS vector database.
	6.	User Query: The user asks a question, and the system searches for the most relevant chunks in the vector database.
	7.	AI Response: The question and context are passed to the Google Gemini AI, which generates the final response.

🗒️ Contributing:

Contributions are welcome! Please follow these steps:
	1.	Fork the repository.
	2.	Create a new branch: git checkout -b feature-name
	3.	Commit your changes: git commit -m "Added new feature"
	4.	Push the branch: git push origin feature-name
	5.	Create a Pull Request.

🛡️ License:

This project is licensed under the MIT License. Feel free to modify and use it for your own purposes.

🎯 Author:
	•	Name: Aman
	•	Email: [amansaini49393@gmail.com]
