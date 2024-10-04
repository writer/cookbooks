# Writer Cookbooks

This repository contains a collection of Jupyter notebooks demonstrating how to use the Writer Python SDK for various AI-related tasks. These notebooks provide practical examples and tutorials for working with our models and services, including model retrieval, text and chat completion, knowledge graph manipulation, and more.

## Table of Contents

- [Writer Cookbooks](#writer-cookbooks)
  - [Table of Contents](#table-of-contents)
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
- A Writer API key ([signup for free](https://app.writer.com/aistudio/signup?utm_campaign=devrel), then follow [this Quickstart](https://dev.writer.com/api-guides/quickstart))

## Installation

Feel free to simply copy and paste the code snippets in the notebooks. If you prefer to run the cookbooks locally, follow these steps:

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

4. Follow the instructions within each notebook to execute the cells and interact with the AI SDK.
   
5. When you’re done using the notebooks, deactivate the virtual environment:
   ```
   deactivate
   ```

## Cookbook descriptions

- Models (`/models`)
  - `model_retrieval.ipynb`: Demonstrates how to retrieve and list available models.
- Completion (`/completion`)
  - `text_completion.ipynb`: Shows how to use the Writer SDK for text completion tasks.
  - `chat_completion.ipynb`: Explores chat-based interactions.
- Knowledge Graphs (`/knowledge_graph`)
  - `knowledge_graph.ipynb`: Introduces the basics of working with files and Knowledge Graphs.

## More resources
- [Writer developer docs](https://dev.writer.com/) - more guides and tutorials can be found here
- [Writer Framework](https://github.com/writer/writer-framework) - our open-source Python framework for rapidly building AI apps 
- [Writer Python SDK](https://github.com/writer/writer-python)  
- [Writer Node SDK](https://github.com/writer/writer-node)  

## About Writer

Writer is the full-stack generative AI platform for enterprises. Quickly and easily build and deploy AI apps with a suite of developer tools fully integrated with our LLMs, graph-based RAG, AI guardrails, and more. To learn more, [visit our website](https://www.writer.com).

## Support

If you encounter any issues or have questions, please file an issue on this repository.
