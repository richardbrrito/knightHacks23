
LegalFlow AI
Overview
This project aims to provide a comprehensive solution for analyzing and categorizing documents using cloud services and AI technologies. It leverages a variety of tools and platforms, including MongoDB Atlas for database management, Google Cloud and Azure AI for document analysis and PDF generation, and Streamlit for creating an interactive web application.

Features
Document Upload and Analysis: Users can upload documents (PDF, PNG, JPG, JPEG) for analysis. The application uses the Azure AI Form Recognizer to extract information from the uploaded documents.
Document Classification: Utilizes custom AI models to classify documents into predefined categories such as Court Order, Medical Record, etc.
PDF Generation: Leverages Google Cloud services to generate PDFs based on the analyzed data.
Interactive Chat Interface: Incorporates LangChain for creating a virtual assistant that can interact with users, providing guidance and responses based on the conversation history.
Customizable UI: The theme of the web application can be customized to fit the Morgan colors scheme.
Technologies Used
Streamlit: For building the web application interface.
Azure AI: For document analysis and classification.
Google Cloud: For PDF generation and cloud computing services.
MongoDB Atlas: For database management and storage.
LangChain: For implementing the chat model and conversation chains.
Setup and Installation
Clone the repository to your local machine.
Install the necessary dependencies by running npm install in the project directory.
Obtain necessary API keys for OpenAI, Azure AI, and Google Cloud services. Update the api_key.py and doc_intel.py files with your credentials.
To start the Streamlit application, run streamlit run app.py in the terminal.
Usage
Navigate to the web application URL provided by Streamlit.
Use the sidebar to upload a document for analysis.
Chat with the virtual assistant for guidance or to ask questions regarding your document.
Based on the analysis, the application will classify your document and provide relevant information.
