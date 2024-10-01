# Search-Engine-with-Langchain-Tools-and-Agents
A chatbot application using Streamlit that allows users to chat with an agent capable of searching the web, querying Arxiv, and Wikipedia.

## Features
- **Real-time Web Search**.
- **Arxiv Query Integration**:
- **Wikipedia Query Integration**:

## Technologies Used
- **LangChain**: A framework to build language model-powered applications.
- **Groq**: Provides access to open-source LLMs via an API.
- **DuckDuckGo**: For web search functionality.
- **Arxiv** and **Wikipedia API Wrappers**: To retrieve information from scientific articles and Wikipedia pages.

## How to Use
1. Enter your `Groq` API key in the sidebar to initialize the LLM. (You can generate an API key by creating an account at [Groq Console](https://console.groq.com/playground)).
2. The chatbot will provide responses based on searches from the web, Arxiv papers, and Wikipedia entries.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/LangChain-Chat-With-Search.git
2. pip install -r requirements.txt
3. streamlit run app.py


