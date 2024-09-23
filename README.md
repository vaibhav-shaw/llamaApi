# LangChain Demo with LLAMA 3.1 API

This project is a demonstration of using LangChain with LLAMA 3.1 for generating essays and poems via API calls. The project uses **FastAPI** for building the backend and **Streamlit** for building the frontend, allowing users to generate content dynamically.

## Project Structure

- **app.py**: The FastAPI server that exposes endpoints to generate essays and poems using LangChain with LLAMA 3.1.
- **client.py**: The Streamlit frontend that interacts with the FastAPI server via API calls.

## Features

- **Generate Essays**: Input a topic to generate a 100-word essay using LLAMA 3.1.
- **Generate Poems**: Input a topic to generate a 100-word poem for a 5-year-old child using LLAMA 3.1.
  
## Requirements

Make sure you have the following installed:

- Python 3.8 or above
- [LangChain](https://github.com/hwchase17/langchain)
- [Streamlit](https://streamlit.io/)
- [FastAPI](https://fastapi.tiangolo.com/)
- [Uvicorn](https://www.uvicorn.org/)
- [dotenv](https://pypi.org/project/python-dotenv/)
- [Requests](https://docs.python-requests.org/en/latest/)
