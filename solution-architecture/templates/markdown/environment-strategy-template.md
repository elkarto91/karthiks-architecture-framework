# Environment Strategy Template Guide

## 1. Purpose
Explains how environments are structured, isolated, and governed.

## 2. Template

### Environment List
| Environment | Purpose | Data Policy | Access Policy | Notes |
|-------------|---------|------------|---------------|-------|
|             |         |            |               |       |

### Promotion Flow
<TODO>

### Configuration Strategy
<TODO>

### Secrets Strategy
<TODO>

### Test Data Strategy
<TODO>

### Release Controls
<TODO>

## 3. Example

| Environment | Purpose | Data Policy | Access Policy |
|-------------|---------|------------|---------------|
| Dev | Developer integration | Synthetic data only | Engineers only |
| Stage | Pre-prod validation | Masked production-like data | Limited team |
| Prod | Live operations | Production data | Strict RBAC |

## 4. Guidance
- Clearly state what is allowed in each environment
- Cover data isolation, approvals, and deployment path