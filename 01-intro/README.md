# Introduction to LLM

## Introduction

Brief introduction to RAG and LLM. Building a toy example of RAG using `minsearch.py`.

## Features

- MinSearch (a toy example of RAG) with OpenAI API

## Installation

Step-by-step guide on how to install the project.

```bash
# Clone the repository
git clone https://github.com/yakhyo/llm-practice.git

# Change directory to the project folder
cd llm-practice

# Change directory to the 01-intro folder
cd 01-intro

# Install dependencies
pip install -r requirements.txt
```

## Elastic Search

Running Elastic Search using docker
```bash
docker run -it \
    --rm \
    --name elasticsearch \
    -p 9200:9200 \
    -p 9300:9300 \
    -e "discovery.type=single-node" \
    -e "xpack.security.enabled=false" \
    docker.elastic.co/elasticsearch/elasticsearch:8.4.3
```