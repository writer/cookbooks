# Writer Cookbooks

This repository contains a collection of Jupyter notebooks demonstrating how to use the Writer Python SDK for various AI-related tasks. These notebooks provide practical examples and tutorials for working with our models and services, including model retrieval, text and chat completion, knowledge graph manipulation, and more.

You can run the cookbooks locally, or, if you prefer, copy and paste the code snippets from the notebooks into your own Python files.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the cookbooks](#running-the-cookbooks)
- [Cookbook descriptions](#cookbook-descriptions)
- [More resources](#more-resources)
- [About Writer](#about-writer)
- [Support](#support)

## Prerequisites

- Python 3.7 or higher
- Jupyter Notebook or JupyterLab
- pip (Python package installer)
- An [AI Studio account](https://app.writer.com/aistudio/signup?utm_campaign=devrel)
- A Writer API key. Follow this [API Quickstart](https://dev.writer.com/api-guides/quickstart) to get your API key.

## Installation

To run the cookbooks locally, follow these setup steps:

1. Clone this repository:
   ```
   git clone https://github.com/writer/cookbooks.git
   cd cookbooks
   ```

2. Create and activate a virtual environment:
   ```
   python -m venv my_env
   source my_env/bin/activate  # On Windows, use `my_env\Scripts\activate`
   ```

3. Once you have an API key, we recommend that you store it as an environment variable in a `.env` file like so:

   ```
   WRITER_API_KEY="{Your Writer API key goes here}"
   ```

## Running the cookbooks

1. Ensure your virtual environment is activated.

2. Start Jupyter Notebook or JupyterLab:
   ```
   jupyter notebook
   ```
   or
   ```
   jupyter lab
   ```

3. Navigate to the notebook you want to run and open it.

4. Follow the instructions within each notebook to execute the cells and interact with the Writer SDK.
   
## Cookbook descriptions

- Applications (`/applications`)
  - `application_basic_usage.ipynb`: Invoke no-code applications using the Writer SDK.
  - `application_graph_management.ipynb`: Attach a Knowledge Graph to a no-code application via the Writer SDK.
  - `application_jobs_utilization.ipynb`: Run no-code applications asynchronously and manage the async jobs.
- Completion (`/completion`)
  - `text_completion.ipynb`: Use the Writer SDK for text completion tasks.
  - `chat_completion.ipynb`: Explores chat-based interactions.
- Knowledge Graphs (`/knowledge_graph`)
  - `knowledge_graph.ipynb`: Introduces the basics of working with files and Knowledge Graphs.
- Models (`/models`)
  - `model_retrieval.ipynb`: Retrieve and list available Palmyra models.
- Tool calling (`/tool_calling`)
  - `tool_calling_api.ipynb`: Introduces the basics of tooling calling and how to use the Writer SDK for tool calling tasks.
  - `tool_calling_kg.ipynb`: Query a Knowledge Graph during a chat.
  - `tool_calling_llm.ipynb`: Invoke a different LLM during a chat with a Palmyra model.
  - `tool_calling_streaming.ipynb`: Use tool calling with streaming responses.
  - `tool_calling_math.ipynb`: Solve a math problem using tool calling.
- Tools (`/tools`)
  - `medical_comprehend.ipynb`: Analyze a medical document and extract entities.
  - `pdf_parser.ipynb`: Parse a PDF file.
  - `text_splitting.ipynb`: Split long text into semantically meaningful chunks.

## More resources
- [Writer developer docs](https://dev.writer.com/)
- [Writer Framework](https://github.com/writer/writer-framework): An open-source Python framework for rapidly building AI apps
- [Writer Framework sample apps](https://github.com/writer/framework-tutorials): Example applications built using the Writer Framework
- [Writer Python SDK](https://github.com/writer/writer-python)  
- [Writer Node SDK](https://github.com/writer/writer-node)  

## About Writer

Writer is the full-stack generative AI platform for enterprises. Quickly and easily build and deploy AI apps with a suite of developer tools fully integrated with our LLMs, graph-based RAG, AI guardrails, and more. To learn more, [visit our website](https://www.writer.com).

## Support

If you encounter any issues or have questions, please file an issue on this repository.
