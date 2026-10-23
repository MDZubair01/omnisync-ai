# OmniSync AI: Autonomous Multi-Device Agent & MCP Hub

Autonomous agent framework and standard-compliant Model Context Protocol (MCP) server for Alexa+ smart device workflows and tool orchestration.

## Features
- **Streamable HTTP Transport:** Compliant with MCP 2025-11-25+ specifications.
- **Dynamic Tool Registry:** Exposes parameterized tools for database telemetry, alerts, and calendar reconciliation.
- **Deterministic Validation:** Pydantic schema validation to prevent LLM hallucinations during tool execution.

## Quickstart
```bash
pip install -r requirements.txt
python server.py
