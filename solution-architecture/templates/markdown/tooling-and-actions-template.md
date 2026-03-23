# Tooling and Actions Template Guide

## 1. Purpose
Defines what external tools, APIs, and systems an agent can use, and what actions it may perform.

## 2. Template

### Tool Inventory

| Tool / API | Purpose | Read / Write | Approval Required | Risk Level | Notes |
|------------|---------|--------------|-------------------|------------|-------|
|            |         |              |                   |            |       |

### Action Categories
- Read-only lookup
- Draft generation
- Recommendation
- Workflow update
- Configuration change
- External execution

### Tool Invocation Rules
<TODO>

### Safe Defaults
<TODO>

### Disallowed Actions
<TODO>

## 3. Example

| Tool / API | Purpose | Read / Write | Approval Required |
|------------|---------|--------------|-------------------|
| Ticket API | Fetch incidents | Read | No |
| Change Mgmt API | Submit change request | Write | Yes |

## 4. Guidance
- Every write action should have a policy
- Classify tools by risk, not only by function
- Keep irreversible actions tightly bounded