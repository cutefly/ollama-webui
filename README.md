# ollama-webui

## Overview

This repository contains a Docker Compose file for setting up an environment with the following components:
- OLLAMA: A model serving platform that allows you to run models in your browser.
- CHROMA: An open-source, vector database that can be used as a backend for storing and querying embeddings.
- DOCLING: A tool for generating documentation from source code.
- REDIS: A popular key-value store that is used by the OLLAMA model server.
- OPEN-WEBUI: An open-source web UI for interacting with the OLLAMA model server.

## Usage
To use this repository, you can run the following command in your terminal:

```bash
docker-compose up -d
```
This will start all of the containers defined in the Docker Compose file. You can then access the Open Web UI at http://localhost:3000.

