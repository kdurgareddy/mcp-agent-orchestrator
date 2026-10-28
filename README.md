# Autonomous MCP Agent Orchestrator

An asynchronous, containerized reasoning engine that integrates tool execution via the **Model Context Protocol (MCP)**. Built with FastAPI, Pydantic v2 validation, and Docker isolation.

## Architecture Highlights
- **Protocol Handling:** Decoupled Model Context Protocol (MCP) tool router.
- **Asynchronous Execution:** Non-blocking async tool calling loops with error recovery.
- **Observability:** Structured logging, step-by-step latency tracking, and execution tracing.
- **Containerization:** Production-ready `Dockerfile` with minimal runtime footprint.

## Tech Stack
- **Backend:** Python 3.11, FastAPI, Uvicorn
- **Validation & Tooling:** Pydantic v2, Model Context Protocol (MCP)
- **Deployment & Testing:** Docker, pytest, pytest-asyncio

## Project Structure
```text
mcp-agent-orchestrator/
├── src/
│   ├── main.py
│   ├── orchestrator.py
│   └── mcp_router.py
├── Dockerfile
├── requirements.txt
└── README.md
