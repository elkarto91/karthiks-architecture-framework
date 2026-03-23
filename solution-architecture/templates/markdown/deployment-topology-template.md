# Deployment Topology Template Guide

## 1. Purpose
Defines how the solution is physically or virtually deployed across environments, regions, sites, cloud accounts, data centers, or edge nodes.

## 2. When to Use
Use this once the logical architecture is reasonably stable and you need to define how it will be hosted and operated.

## 3. Template

### Deployment Model
Examples:
- Single-tenant SaaS
- Multi-tenant SaaS
- Hybrid SaaS
- Customer-hosted
- On-premises enterprise deployment
- Edge + cloud deployment
- Site-local + central control plane

### Hosting Locations
- <Region / Data Center / Site 1>
- <Region / Data Center / Site 2>

### Deployment Units
| Unit | Description | Runs Where | HA Strategy | Notes |
|------|-------------|------------|-------------|-------|
|      |             |            |             |       |

### Environment Layout
- Development
- Test
- Staging
- Production
- DR / Secondary

### Regional / Site Strategy
<TODO>

### Network Zones / Boundaries
<TODO>

### Resilience Notes
<TODO>

## 4. Example

### Deployment Model
Hybrid SaaS with regional control plane and optional customer edge agents.

### Deployment Units
| Unit | Description | Runs Where | HA Strategy |
|------|-------------|------------|-------------|
| API Platform | External API services | Cloud region primary | Multi-AZ |
| Event Bus | Internal messaging | Cloud region primary | Managed HA |
| Edge Gateway | Site-local gateway | Customer site | Active/passive per site |

## 5. Guidance
- Focus on runtime placement and topology
- Keep logical and physical concerns separate
- Must align with networking, resilience, and sizing docs