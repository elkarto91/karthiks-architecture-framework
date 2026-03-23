# Agent Overview Template Guide

## 1. Purpose
Defines the overall role of AI agents in the system, including their scope, responsibilities, boundaries, and operating model.

## 2. When to Use
Use this when AI is a first-class part of the product, platform, operations model, or enterprise knowledge layer.

## 3. Template

### AI / Agent Vision
<TODO>

### Agent Operating Model
Examples:
- Advisory only
- Human-in-the-loop
- Semi-autonomous
- Fully automated for bounded tasks

### Agent Scope
- <Scope 1>
- <Scope 2>

### Agent Boundaries
- <Boundary 1>
- <Boundary 2>

### Agent Types
| Agent | Purpose | Reads | Writes / Acts | Human Approval Required | Notes |
|-------|---------|-------|---------------|-------------------------|-------|
|       |         |       |               |                         |       |

### Supported Business Areas
<TODO>

### Excluded Areas
<TODO>

### Key Risks
<TODO>

## 4. Example

### AI / Agent Vision
Provide a platform assistant that helps users navigate workflows, retrieve relevant information, and recommend next actions, while keeping all irreversible actions behind approval.

### Agent Operating Model
Human-in-the-loop for operational actions; advisory for architecture and analytics.

### Agent Types
| Agent | Purpose | Reads | Writes / Acts | Human Approval Required |
|-------|---------|-------|---------------|-------------------------|
| Support Copilot | Help support teams resolve issues | Knowledge base, logs | Draft responses | Yes |
| Workflow Agent | Suggest next task step | Tickets, workflow state | Update workflow status | Yes |
| Architecture Assistant | Explain system design | Docs, ADRs, diagrams | Draft architecture notes | Yes |

## 5. Guidance
- Start by defining what the agent should NOT do
- Separate advisory use cases from action-taking use cases
- Always state approval boundaries explicitly
- Link this file to security, data, and tooling sections