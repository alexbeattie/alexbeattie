# Alex Beattie

**AI/LLM Engineer** building retrieval-augmented generation systems, multi-agent orchestration, and production AI applications. Focused on practical, cost-efficient AI that runs locally or on AWS.

[Blog](https://alexbeattie.com) | [LinkedIn](https://linkedin.com/in/alexbeattie)

## AI & LLM Projects

### [obsidian-rag](https://github.com/alexbeattie/obsidian-rag)
Fully offline RAG pipeline that indexes an Obsidian vault into ChromaDB using heading-based semantic chunking and nomic-embed-text embeddings via Ollama. Includes an MCP server so coding agents (Cursor, Claude Code) can query the vault during development. Interactive REPL with streaming LLM responses and source citations.

**Stack:** Python, ChromaDB, Ollama, FastMCP, nomic-embed-text, mistral-nemo

### [llm-eval-harness](https://github.com/alexbeattie/llm-eval-harness)
Lightweight evaluation framework for RAG pipelines. Three layers: retrieval metrics (recall@k, precision@k, MRR), LLM-as-Judge response scoring (relevance, groundedness, completeness), and claim-level hallucination detection. ~300 lines, zero framework dependencies.

**Stack:** Python, Ollama, LLM-as-Judge pattern

### [model-router](https://github.com/alexbeattie/model-router)
Intelligent query routing that classifies complexity with zero-latency heuristics and directs simple queries to a fast model, complex queries to a capable model. Reduces inference costs ~70% while maintaining quality. 100% accuracy on built-in benchmark.

**Stack:** Python, Ollama, regex-based classification


## Production Apps

### [CHLA / KiNDD Resource Navigator](https://github.com/alexbeattie/CHLA)
Healthcare provider mapping app with Django/PostGIS backend and native SwiftUI iOS app. AI-powered search using AWS Bedrock with Strands SDK. [Live on the App Store.](https://apps.apple.com/us/app/kindd-resource-navigator/id6756593861)

**Stack:** Python, Django, PostGIS, AWS Bedrock, SwiftUI, iOS

### [OneStepGPS](https://github.com/alexbeattie/OneStepGPS)
Real-time GPS vehicle tracking app with Vue.js frontend and Go backend.

**Stack:** Vue.js, Go, REST APIs

## What I Work With

**AI/ML:** RAG pipelines, multi-agent orchestration, LLM-as-Judge evaluation, model routing, vector databases (ChromaDB, pgvector), embedding models, MCP servers, Ollama, AWS Bedrock

**Backend:** Python, Django, Go, Node.js, GraphQL, REST APIs

**Cloud:** AWS (ECS, Lambda, Bedrock, Aurora), Docker, CI/CD

**Frontend & Mobile:** Vue.js, React, SwiftUI, Flutter
