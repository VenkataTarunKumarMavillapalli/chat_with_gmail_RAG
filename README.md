## 📨 Chat with Gmail Inbox 

LLM app with RAG to chat with Gmail. The app uses Retrieval Augmented Generation (RAG) to provide accurate answers to questions based on the content of your Gmail Inbox.

### Features

- Connect to your Gmail Inbox
- Ask questions about the content of your emails
- Get accurate answers using RAG and the selected LLM

### Installation

1. Set up your Google Cloud project and enable the Gmail API:

- Go to the [Google Cloud Console](https://console.cloud.google.com/) and create a new project.
- Navigate to "APIs & Services > OAuth consent screen" and configure the OAuth consent screen.
- Publish the OAuth consent screen by providing the necessary app information.
- Enable the Gmail API and create OAuth client ID credentials.
- Download the credentials in JSON format and save them as `credentials.json` in your working directory.

2. Get your OpenAI API Key

- Sign up for an [OpenAI account](https://platform.openai.com/) (or the LLM provider of your choice) and obtain your API key.
