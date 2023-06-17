# LLMQueryAnalyzer

This project aims to address the common issue of poor retrieval in search systems powered by Large Language Models (LLMs). With the increasing usage of LLMs for chatbots and search systems, it is crucial to efficiently build and analyze the LLM to ensure optimal performance and user satisfaction. This repository provides a solution for understanding the questions users ask and evaluating the quality of the answers provided by an LLM-based question-answering service.


## Project Overview

The main objective of this project is to analyze the performance of an LLM question-answering service that interacts with a pre-indexed knowledge base. By examining user queries and the corresponding answers, we can identify areas where the system falls short, particularly when there is a lack of relevant context to provide accurate responses. This analysis can guide improvements to the LLM model and help fine-tune its performance.

## Features

This project offers the following features:

1. **Downloading Pre-Indexed Knowledge Base**: The notebook provides functionality to download a pre-indexed knowledge base, which serves as the data source for the LLM question-answering service.

2. **Running LlamaIndex Application**: With the downloaded knowledge base, the notebook facilitates the execution of the LlamaIndex application. This application leverages embeddings computed using the OpenAI API, allowing efficient querying of the knowledge base.

3. **Analyzing User Query Clusters**: By investigating clusters of user queries, we can identify patterns and assess the quality of the LLM's responses. The notebook employs Phoenix, a powerful analysis tool, to examine areas where there is a density of queries without sufficient context.

4. **Identifying Overlap between Queries and Context**: Understanding the overlap between user queries and available context is crucial for improving the LLM. This project helps in identifying whether there is a decent overlap and provides insights into areas where the context is lacking.

5. **Fine-Tuning the LLM Model**: Based on the analysis results, the notebook suggests the next steps to fine-tune the LLM model. These steps can include gathering more data to cover areas with limited context or adjusting the model's parameters to enhance retrieval performance.

## Usage

To use this project, follow these steps:

1. Clone the repository to your local machine.

2. Download the provided notebook and open it in a Jupyter Notebook or compatible environment.

3. Set up the necessary configuration parameters, such as API keys, knowledge base URL, and analysis settings.

4. Run the notebook cells sequentially, following the instructions and explanations provided.

5. Analyze the output and observations to gain insights into the performance of your LLM question-answering service.

6. Utilize the findings to improve your LLM model, such as by addressing areas with insufficient context or adjusting the model's behavior.


## Acknowledgments

This project makes use of the following technologies and libraries:

- OpenAI API: Provides the LLM capabilities for question-answering and embedding computation.
- Phoenix: A powerful analysis tool used for investigating query clusters and identifying areas with limited context.
- Jupyter Notebook: An interactive computing environment for running and sharing code.

This project was in part of a workshop hosted by Arizeai:https://lu.ma/Arize-Llamaindex-Workshop
