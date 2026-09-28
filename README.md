## Building AI agents on open-source models

I build agentic and generative AI systems that run on **open-weight models, locally**.
No closed APIs, no per-token bills: just models you can inspect, run and own.

My focus is the engineering that turns an LLM demo into something dependable:
validated outputs, grounded answers, planning loops that stop, and systems you
can observe.

### What I'm working on

**[omlx_agents](https://github.com/cowtree/omlx_agents)**: twelve production
agent patterns, built one at a time, all running on open models served locally
by oMLX on Apple Silicon.

| | Agent pattern | Status |
|---|---|---|
| 1 | Structured output with validation and retries | ✅ Done |
| 2 | RAG with citation grounding | 🚧 In progress |
| 3 | ReAct planning agent | Planned |
| 4 | Multi-tool orchestrator | Planned |
| 5 | Memory-enabled conversational agent | Planned |
| 6 | Human-in-the-loop approval | Planned |
| 7 | Cost-aware model router | Planned |
| 8 | Event-triggered automation | Planned |
| 9 | Multi-agent debate | Planned |
| 10 | Self-reflective agent with auto-evaluation | Planned |
| 11 | Production observability | Planned |
| 12 | Open-source agent framework contribution | Planned |

### Focus areas

- **Agentic AI:** planning loops, tool use, memory, multi-agent collaboration, human approval
- **Generative AI:** structured outputs, retrieval-augmented generation, self-evaluation
- **Open-source models:** local inference, model routing, running without paid APIs
- **Production readiness:** validation, retries, logging, testing and observability

### Stack

Python · Pydantic · OpenAI-compatible APIs · oMLX / MLX · Qwen · FastAPI · pytest · uv

### Earlier work

- [financial_news_agents](https://github.com/cowtree/financial_news_agents): a multi-agent financial news aggregator that fetches, scores and summarizes news on a local open-source model
- [dynamic_risk_assessment_mlops](https://github.com/cowtree/dynamic_risk_assessment_mlops): ML automation in production
- [udacity_mldevops_project3](https://github.com/cowtree/udacity_mldevops_project3): deploying an ML model with FastAPI

### Connect

[LinkedIn](https://www.linkedin.com/in/caotrido/)
