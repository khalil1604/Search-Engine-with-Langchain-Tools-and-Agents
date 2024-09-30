# Search-Engine-with-Langchain-Tools-and-Agents
An interactive chatbot application using LangChain and Streamlit that allows users to chat with an agent capable of searching the web, querying Arxiv, and Wikipedia.

## Features
- **Real-time Web Search**: Use DuckDuckGo search engine for retrieving the latest information.
- **Arxiv Query Integration**: Retrieve scientific papers with summarized content.
- **Wikipedia Query Integration**: Extract concise information from Wikipedia.
- **Interactive Chat Interface**: Engage with the chatbot directly in the Streamlit app.

## Technologies Used
- **Streamlit**: For building the interactive web application.
- **LangChain**: A framework to build language model-powered applications.
- **Groq**: Provides access to open-source LLMs via an API.
- **DuckDuckGo**: For web search functionality.
- **Arxiv** and **Wikipedia API Wrappers**: To retrieve information from scientific articles and Wikipedia pages.

## How to Use
1. Enter your `Groq` API key in the sidebar to initialize the LLM. (You can generate an API key by creating an account at [Groq Console](https://console.groq.com/playground)).
2. Start chatting with the bot using the chat input field.
3. The chatbot will provide responses based on searches from the web, Arxiv papers, and Wikipedia entries.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/LangChain-Chat-With-Search.git
2. pip install -r requirements.txt
3. streamlit run app.py


