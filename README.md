# ConstructingKnowledgeGgraphs
Constructing a Knowledge Graph from Unstructured Text

This guide outlines the basic steps for constructing a knowledge graph based on unstructured text, which can then be utilized as a knowledge base in a RAG (Retrieval-Augmented Generation) application.

## Architecture

At a high level, the process of constructing a knowledge graph from text involves the following steps:

1. **Extracting Structured Information from Text:** Utilizing a model to extract structured graph information from unstructured text.
   
2. **Storing into Graph Database:** Storing the extracted structured graph information into a graph database to enable downstream RAG applications.

## LLM Graph Transformer

The LLM (Language Model) Graph Transformer is a crucial component in this process. It facilitates the extraction of graph data from text, enabling the transformation of unstructured information into structured formats. This transformation allows for deeper insights and more efficient navigation through complex relationships and patterns.

The LLMGraphTransformer achieves this by converting text documents into structured graph documents. It leverages a Language Model (LLM) to parse and categorize entities and their relationships within the text. The selection of the LLM model significantly influences the accuracy and nuance of the extracted graph data.
