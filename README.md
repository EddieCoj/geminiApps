# geminiApps
This project stands as a testament to the transformative power of AI in solving real-world problems and creating value for society.

Gemini Pro LLM Applications: This repository contains multiple Python projects developed as part of a capstone project. Each project is designed to solve a specific problem, using various libraries and APIs. Below you'll find instructions for setting up and running the projects.

## Prerequisites
Before running any of the projects, ensure you have Python installed on your system. You will also need to install the required libraries specified in the `requirements.txt` file.
Explanation of the packages:
streamlit: The web app framework you are using.
google-generativeai: For interacting with Google's generative AI models.
PyPDF2: For handling PDFs (reading and parsing).
python-dotenv: For loading environment variables from .env files.
Pillow: A library for image processing (for the image functions).
langchain: The core framework for handling text processing, question answering, and more.
langchain-google-genai: The Langchain integration for Google Generative AI.
langchain-community: Includes additional integrations for vector stores like FAISS.
faiss-cpu: The FAISS library for fast similarity search, which you need for your vector store.
sqlite3: For managing SQLite databases.
youtube-transcript-api: To fetch YouTube video transcripts.

## Setup
### Clone the Repository
git clone https://github.com/EddieCoj/geminiApps.git
cd geminiApps
### Install Dependencies
pip install -r requirements.txt
### Set Up API Key
Some of the projects in this repository require access to Google's Gemini Pro API. To use these projects, you'll need to create your own API key and store it in an .env file. 
Create a file named .env in the root directory of the repository.
Paste your Google Gemini Pro API key into the file as follows:
GOOGLE_API_KEY="your_api_key_here"
Replace your_api_key_here with your actual API key. You can obtain the API key from Google's API Studio. https://aistudio.google.com/app/apikey

# Project Descriptions
## 1. ATS Resume
A tool that allows users to build and analyze their resumes against ATS (Applicant Tracking Systems) criteria.

## 2. Chat with PDFs
Enables users to chat with the content of PDF files using AI.

## 3. Text to SQL Query Generator
Automatically converts plain text into SQL queries.

## 4. Health View
An application for visualizing health-related data.

## 5. YouTube Video Transcriber & Chat with Video Content
Transcribes YouTube videos and allows users to interact with the transcribed content.


## Running the Projects
Each project can be run using Streamlit. For example, to run the "Chat with PDFs" project:
"streamlit run chat_with_pdfs.py"
Replace chat_with_pdfs.py with the appropriate script for the project you want to run.










