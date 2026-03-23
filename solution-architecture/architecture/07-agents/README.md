# 07 Agents

## Purpose
This section defines how AI agents participate in the system, what context they use, what actions they can take, and how they are governed.

It explains:
- the overall AI / agent operating model
- business and operational use cases
- context sources and knowledge inputs
- RAG design and retrieval rules
- memory model
- tools and action boundaries
- guardrails and controls
- evaluation and human oversight

## Contents
- `agent-overview.md` — overall AI / agent role in the system
- `agent-use-cases.md` — business and operational use cases
- `agent-context-sources.md` — source systems and documents used as context
- `agent-roles.md` — distinct agent roles and responsibilities
- `rag-design.md` — retrieval and context assembly design
- `memory-model.md` — memory scope, persistence, and constraints
- `tooling-and-actions.md` — tools, APIs, and allowed actions
- `guardrails.md` — safety, policy, and validation controls
- `evaluation.md` — quality, safety, and usefulness metrics
- `human-in-the-loop.md` — review and approval boundaries

## Subsections
- `a-context/` — context-source decomposition
- `b-retrieval/` — retrieval, metadata, and freshness rules
- `c-reasoning/` — orchestration and routing logic
- `d-actions/` — tool/action definitions and approval flows
- `e-governance/` — model governance, benchmarks, and compliance

## Related Documents
- `../02-business/`
- `../03-solution/`
- `../05-security/`
- `../06-data/`