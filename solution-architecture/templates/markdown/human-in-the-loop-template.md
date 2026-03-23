# Human in the Loop Template Guide

## 1. Purpose
Defines where humans must review, approve, or intervene in agent workflows.

## 2. Template

### HITL Principles
<TODO>

### Approval Points
| Workflow | Trigger | Human Role | Approval Needed | Notes |
|----------|---------|------------|-----------------|-------|
|          |         |            |                 |       |

### Escalation Paths
<TODO>

### Override Rules
<TODO>

### Audit Requirements
<TODO>

## 3. Example

| Workflow | Trigger | Human Role | Approval Needed |
|----------|---------|------------|-----------------|
| Incident recommendation | Sev-1 incident | On-call engineer | Yes |
| Architecture draft generation | New design request | Architect | Yes |

## 4. Guidance
- Specify approval before action, not after
- High-risk domains should default to human control