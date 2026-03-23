# ADR Writing Guidelines

## Purpose
Defines how to write high-quality ADRs.

---

## What Makes a Good ADR

### 1. Clear Context
Explain WHY the decision is needed.

### 2. Explicit Decision
Avoid vague wording.

Bad:
"Consider using Kafka"

Good:
"Kafka will be used as the primary event streaming platform"

### 3. Real Alternatives
Include at least 2–3 alternatives.

### 4. Honest Trade-offs
Every decision has downsides — document them.

### 5. Traceability
Link to:
- business goals
- solution components
- risks

---

## Anti-Patterns

❌ Writing ADR after implementation  
❌ No alternatives listed  
❌ No consequences  
❌ Overly technical without business context  
❌ Duplicate ADRs  

---

## Naming Convention

ADR-0001: Initial Architecture Approach  
ADR-0002: Event Bus Selection  
ADR-0003: Multi-Tenant Strategy  

---

## When to Create an ADR

Create an ADR when:

- introducing a major component
- choosing between multiple architectures
- defining a core pattern
- making irreversible decisions
- impacting multiple teams/projects
- affecting security/compliance
- defining AI/agent behavior boundaries