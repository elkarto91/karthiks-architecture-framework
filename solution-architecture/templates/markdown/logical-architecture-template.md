# Logical Architecture Template Guide

## 1. Purpose
Defines the major logical components of the solution and their responsibilities.

## 2. Template

### Logical View Overview
<TODO>

### Component List

| Component | Responsibility | Interfaces | Notes |
|-----------|----------------|------------|-------|
|           |                |            |       |

### Interaction Model
<TODO>

### Boundaries and Ownership
<TODO>

### Shared Services
<TODO>

### Domain Separation
<TODO>

## 3. Example

### Component List

| Component | Responsibility | Interfaces |
|-----------|----------------|------------|
| API Gateway | External API entry point | REST |
| Payment Orchestrator | Manages payment lifecycle | Internal APIs, Events |
| Compliance Engine | Sanctions, rules, checks | Internal APIs |
| Wallet Service | Address and signing management | Internal APIs |

## 4. Guidance
- This is logical, not physical deployment
- Group by responsibility, not by code repository
- Use alongside C4 container/component diagrams