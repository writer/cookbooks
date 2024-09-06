# Writer Cookbooks

This repository contains a collection of Jupyter notebooks demonstrating how to use the Writer Python SDK for various AI-related tasks. These notebooks provide practical examples and tutorials for working with our models and services, including model retrieval, text and chat completion, knowledge graph manipulation, and more.

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Installation](#installation)
3. [Running the cookbooks](#running-the-cookbooks)
4. [Cookbook descriptions](#cookbook-descriptions)
5. [More resources](#more-resources)
5. [About Writer](#about-writer)

## Prerequisites

- Python 3.7 or higher
- Jupyter Notebook or JupyterLab
- pip (Python package installer)
- A Writer API key ([signup for free](https://app.writer.com/aistudio/signup?utm_campaign=devrel), the follow [this Quickstart](https://dev.writer.com/api-guides/quickstart))

## Installation

Feel free to simply copy and paste the code snippets in the notebooks. If you prefer to run the cookbooks locally, follow these steps:

1. Clone this repository:
   ```
   git clone https://github.com/writer/cookbooks.git
   cd cookbooks
   ```

2. Create and activate a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
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
