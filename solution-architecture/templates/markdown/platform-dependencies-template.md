# Platform Dependencies Template Guide

## 1. Purpose
Lists the foundational platform services and third-party dependencies required by the solution.

## 2. Template

| Dependency | Category | Used For | Criticality | Owner / Vendor | Notes |
|------------|----------|----------|-------------|----------------|-------|
|            |          |          |             |                |       |

### Dependency Risks
<TODO>

### Vendor Lock-in Notes
<TODO>

### Fallback / Exit Strategy
<TODO>

## 3. Example

| Dependency | Category | Used For | Criticality |
|------------|----------|----------|-------------|
| Cloud KMS | Security platform | Key management | High |
| Kafka | Messaging | Event distribution | High |
| External IAM | Identity | SSO | High |

## 4. Guidance
- Include both internal shared platforms and external vendor services
- Important for architecture review and procurement risk