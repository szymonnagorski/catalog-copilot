# Catalog copilot
This is an AI assistant for a B2B product catalog built on synthetic data

## Roadmap
1. **Chat + tools** — streaming chat that searches products, checks stock and prices a cart.
2. **RAG + evals** — answers questions from product documentation with citations, measured by an automated eval suite in CI.
3. **Agent + MCP + security** — an ordering agent with human approval, tools exposed via an MCP server, hardened against prompt injection.
4. **Production + LLMOps** — deployed behind a gateway with caching, fallbacks, cost limits and tracing.
