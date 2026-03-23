# RAG Design Template Guide

## 1. Purpose
Defines how retrieval-augmented generation is implemented for the agent.

## 2. Template

### RAG Objectives
<TODO>

### Corpus Scope
<TODO>

### Chunking Strategy
<TODO>

### Metadata Strategy
<TODO>

### Retrieval Strategy
Examples:
- lexical + vector hybrid
- metadata-filtered vector retrieval
- graph-assisted retrieval
- hierarchical retrieval
- project-first, portfolio-second retrieval

### Ranking / Re-ranking
<TODO>

### Context Assembly
<TODO>

### Citation / Traceability Model
<TODO>

### Failure Handling
<TODO>

### Evaluation Approach
<TODO>

## 3. Example

### Retrieval Strategy
Use hybrid retrieval with metadata filters for project, environment, doc type, and confidentiality.

### Context Assembly
Top 3 authoritative documents + related ADRs + latest operational summary.

## 4. Guidance
- Prefer authoritative, typed, and recent content
- Retrieval rules should differ for design, ops, and compliance queries
- Always define how citations or evidence will be preserved