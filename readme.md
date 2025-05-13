# AI Research Assistant

This project provides an AI-powered research assistant tool that helps users conduct research by searching the web, summarizing results, and generating a response to a specific query. It uses LangChain, Tavily for search results, and Ollama for generating summaries and responses. The tool is built using Streamlit for an interactive web interface.

## Features

- **Web Search**: Automatically searches for relevant results based on the user's query using the Tavily search tool.
- **Summarization**: Summarizes the web results into concise paragraphs that address the user's query directly.
- **Response Generation**: Combines the summarized content and generates a clear, concise, and well-structured response to the query.
- **Source Display**: Shows the sources from which the results were gathered, providing full transparency.

## Requirements

Before running the project, ensure that you have the following libraries installed:

- `streamlit` - For building the web interface.
- `langchain` - For building the research assistant workflow.
- `langchain_ollama` - For integrating Ollama's language models.
- `langchain_community` - For utilizing Tavily search.
- `python-dotenv` - For loading environment variables.
- `re` - For text cleaning.
- `re`, `typing_extensions` - For type definitions.

To install these dependencies, run:

```bash
pip install streamlit langchain langchain_ollama langchain_community python-dotenv