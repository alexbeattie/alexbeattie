# Alex Beattie

I build production AI systems, agent tooling, and healthcare software.

Recently I have been focused on retrieval-augmented generation, MCP servers,
LLM evaluation, AWS Bedrock, and mobile/backend systems that ship to real users.

[Blog](https://alexbeattie.com) | [LinkedIn](https://linkedin.com/in/alexbeattie)

## Featured Work

### Unified Connectors MCP Server
An installable Python package and MCP server that lets AI agents work across
GitHub, Slack, Jira, Confluence, Google Docs, and Miro from one consistent
action layer. Includes a CLI, provider connectors, OAuth refresh handling,
webhook helpers, and a full test suite.

**Stack:** Python, Model Context Protocol, FastMCP, OAuth 2.0, GitHub API,
Slack API, Atlassian Cloud, Google Docs/Drive API, Miro API

### Ourself Health / Stella
Production health AI backend for Stella, an LLM-powered assistant with
source-grounded RAG, streaming responses, clinical knowledge retrieval,
Langfuse observability, and evaluation workflows. Runs on Django, Strawberry
GraphQL, AWS ECS Fargate, Aurora PostgreSQL/pgvector, Bedrock, Auth0, and
Flutter mobile clients.

**Stack:** Python, Django, Strawberry GraphQL, AWS Bedrock, pgvector, Aurora,
ECS Fargate, Langfuse, Auth0, Flutter

### [obsidian-rag](https://github.com/alexbeattie/obsidian-rag)
Local-first RAG pipeline that indexes an Obsidian vault into ChromaDB using
heading-aware semantic chunking and Ollama embeddings. Includes an MCP server
so coding agents can query the vault during development, plus a REPL with
streaming responses and citations.

**Stack:** Python, ChromaDB, Ollama, FastMCP, nomic-embed-text, mistral-nemo

### [llm-eval-harness](https://github.com/alexbeattie/llm-eval-harness)
Small evaluation framework for RAG systems: retrieval metrics, LLM-as-judge
response scoring, and claim-level hallucination checks without a heavy
framework dependency.

**Stack:** Python, Ollama, LLM-as-judge evaluation

### [model-router](https://github.com/alexbeattie/model-router)
Query router that classifies request complexity and sends simple requests to a
fast local model while reserving stronger models for harder tasks.

**Stack:** Python, Ollama, routing heuristics, cost-aware inference

## Shipped Apps

### [CHLA / KiNDD Resource Navigator](https://github.com/alexbeattie/CHLA)
Healthcare provider mapping app with a Django/PostGIS backend and native
SwiftUI iOS app. Uses AWS Bedrock and Strands SDK for AI-powered search.
[Live on the App Store.](https://apps.apple.com/us/app/kindd-resource-navigator/id6756593861)

**Stack:** Python, Django, PostGIS, AWS Bedrock, SwiftUI, iOS

### [OneStepGPS](https://github.com/alexbeattie/OneStepGPS)
Real-time GPS vehicle tracking app with a Vue.js frontend and Go backend.

**Stack:** Vue.js, Go, REST APIs

## Tools I Reach For

**AI/Agents:** RAG pipelines, MCP servers, multi-agent orchestration,
LLM-as-judge evals, model routing, vector search, Ollama, AWS Bedrock

**Backend:** Python, Django, GraphQL, Go, Node.js, REST APIs, Postgres

**Cloud:** AWS ECS, Lambda, Bedrock, Aurora, S3, Docker, GitHub Actions

**Frontend & Mobile:** Flutter, SwiftUI, Vue.js, React
