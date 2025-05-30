# LangChain Tutorial Playground

This repository serves as a hands-on playground for the official LangChain tutorial, specifically adapted for **version 0.3**. It's designed to help you follow along and experiment with the concepts introduced in the [official documentation](https://python.langchain.com/docs/tutorials/).

-----

## Getting Started

To run the examples and explore the LangChain functionalities in this repository, you'll need to set up your environment with the necessary API keys.

-----

### Environment Setup

Create a file named `.env` in the root directory of this project. Populate it with your API keys and configuration details, following this structure:

```text
LANGSMITH_TRACING=true
LANGSMITH_ENDPOINT="https://api.smith.langchain.com"
LANGSMITH_API_KEY="your_langsmith_api_key_here"
LANGSMITH_PROJECT="your_langsmith_project_name"
OPENAI_API_KEY="your_openai_api_key_here"
```

**Note:** Replace the placeholder values (e.g., `your_langsmith_api_key_here`) with your actual API keys.

-----

### Installation

Before running the code, make sure you have all the required dependencies installed. You can typically do this using `conda`:

```bash
conda env create -f environment.yml
```

-----

## What's Inside?

This repository contains:

  * **Jupyter Notebooks/Python Scripts:** Each notebook corresponds to a specific section of the LangChain tutorial.

-----

## Contributing

-----

Feel free to fork this repository, experiment with the code, and even contribute your own enhancements or examples\!

-----

## License

-----

Apache License v2.0