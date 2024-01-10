# neo4j-app

This deploys the [neo4j-semantic-layer](https://github.com/langchain-ai/langchain/tree/master/templates/neo4j-semantic-layer) semantic layer template.

## Installation

Install the LangChain CLI if you haven't yet

```bash
pip install -U langchain-cli
```

## Create app and add neo4j-semantic-layer package

```bash
langchain app new . 
What package would you like to add? (leave blank to skip): neo4j-semantic-layer  
```

## Run locally
```
langchain serve
```

Ensure API keys are set:

```
OPENAI_API_KEY=<YOUR_OPENAI_API_KEY>
NEO4J_URI=<YOUR_NEO4J_URI>
NEO4J_USERNAME=<YOUR_NEO4J_USERNAME>
NEO4J_PASSWORD=<YOUR_NEO4J_PASSWORD>
```

## Run with hosted LangServe

Use LangSmith console to import this repo.