# Agent Context Sources Template Guide

## 1. Purpose
Defines the data, documents, systems, and signals that provide context to the agent.

## 2. Template

### Context Source Inventory

| Source | Type | Purpose | Freshness | Access Mode | Sensitivity | Notes |
|--------|------|---------|-----------|-------------|-------------|-------|
|        |      |         |           |             |             |       |

### Context Categories
- Business documents
- Architecture documents
- ADRs
- Runbooks
- APIs and schemas
- Ticketing / work items
- Operational telemetry
- Data products
- Site / asset metadata
- Regulatory / policy content

### Source Prioritization Rules
<TODO>

### Source-of-Truth Rules
<TODO>

### Freshness Rules
<TODO>

### Excluded Sources
<TODO>

## 3. Example

| Source | Type | Purpose | Freshness | Access Mode | Sensitivity |
|--------|------|---------|-----------|-------------|-------------|
| ADR Repository | Markdown docs | Decision rationale | Medium | Read-only | Internal |
| Runbooks | Knowledge docs | Incident recovery guidance | High | Read-only | Internal |
| Ticketing System | Structured records | Current work context | High | API | Internal |

## 4. Guidance
- Be explicit about what is authoritative vs reference-only
- Freshness matters as much as relevance
- This section is critical for RAG quality and auditability