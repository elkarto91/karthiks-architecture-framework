# Solution Strategy Template Guide

## 1. Purpose
Defines the overall architectural approach used to meet the business goals.  
This explains the high-level solution style and major design choices before diving into detailed components.

## 2. When to Use
Use this early in architecture definition, after business context is understood and before detailed logical design.

## 3. Template

### Problem Being Solved
<TODO>

### Solution Vision
<TODO>

### Architectural Style
Examples:
- Modular monolith
- Microservices
- Event-driven architecture
- Workflow-driven platform
- API-first platform
- Edge + cloud hybrid
- Agentic orchestration platform

### Core Design Principles
- <Principle 1>
- <Principle 2>

### Major Building Blocks
- <Block 1>
- <Block 2>

### Key Architectural Decisions
- <Decision 1>
- <Decision 2>

### Benefits of This Strategy
<TODO>

### Trade-offs
<TODO>

### Alternatives Considered
<TODO>

## 4. Example

### Problem Being Solved
Banks and fintech partners need a compliant stablecoin payments platform without directly handling blockchain complexity.

### Solution Vision
A modular platform combining wallet services, compliance services, payment orchestration, and blockchain connectivity through a unified API layer.

### Architectural Style
API-first, modular services, event-driven processing.

### Core Design Principles
- Separation of orchestration from execution
- Compliance as a first-class service
- Vendor-neutral blockchain abstraction
- Strong observability and auditability

### Major Building Blocks
- API Gateway
- Payment Orchestrator
- Compliance Engine
- Wallet Service
- Blockchain Connector
- Reporting Service

### Key Architectural Decisions
- Use async events for transaction state changes
- Separate customer-facing APIs from internal processing services

## 5. Guidance
- Keep this high-level and directional
- Do not turn this into a component inventory
- Focus on why this architecture shape is chosen
- Must be traceable to business goals and constraints