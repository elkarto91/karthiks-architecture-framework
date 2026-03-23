# Compute and Storage Template Guide

## 1. Purpose
Describes the major compute, runtime, and storage building blocks used by the platform.

## 2. Template

### Compute Landscape
| Component | Runtime Type | Scaling Model | Notes |
|-----------|--------------|---------------|-------|
|           |              |               |       |

### Storage Landscape
| Store | Type | Purpose | Retention | Notes |
|-------|------|---------|-----------|-------|
|       |      |         |           |       |

### Caching Strategy
<TODO>

### Backup Strategy
<TODO>

### Performance Considerations
<TODO>

## 3. Example

### Compute Landscape
| Component | Runtime Type | Scaling Model |
|-----------|--------------|---------------|
| API Services | Kubernetes pods | Horizontal |
| Workflow Engine | Managed service | Auto-scale |
| Edge Agent | VM / appliance | Per site |

### Storage Landscape
| Store | Type | Purpose |
|-------|------|---------|
| PostgreSQL | Relational | Transactions |
| Object Storage | Blob | Files and exports |
| Redis | Cache | Session and hot reads |

## 4. Guidance
- Keep this focused on major technology choices and patterns
- Avoid instance-level deployment detail here