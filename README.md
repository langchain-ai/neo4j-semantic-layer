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

Open the playground:
```
http://127.0.0.1:8000/neo4j-semantic-layer/playground/
```

![Screenshot 2024-01-10 at 12 09 58 PM](https://github.com/langchain-ai/neo4j-semantic-layer/assets/122662504/74fefcc3-dded-49f7-8d85-949899de3ba0)

Ensure API keys are set:

```
OPENAI_API_KEY=<YOUR_OPENAI_API_KEY>
NEO4J_URI=<YOUR_NEO4J_URI>
NEO4J_USERNAME=<YOUR_NEO4J_USERNAME>
NEO4J_PASSWORD=<YOUR_NEO4J_PASSWORD>
```

## Run with hosted LangServe

Use LangSmith console to import this repo.

![Screenshot 2024-01-10 at 12 14 31 PM](https://github.com/langchain-ai/neo4j-semantic-layer/assets/122662504/16b4ac2a-6e83-45d5-b764-28d9294123b1)
