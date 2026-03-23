# Networking Template Guide

## 1. Purpose
Defines network topology, segmentation, connectivity, and security-relevant network flows.

## 2. Template

### Network Overview
<TODO>

### Zones / Segments
- Public ingress
- Private application zone
- Data zone
- Management zone
- Edge / site zone
- OT / plant zone
- DMZ

### Connectivity Matrix
| Source | Destination | Purpose | Protocol / Port | Notes |
|--------|-------------|---------|-----------------|-------|
|        |             |         |                 |       |

### External Connectivity
<TODO>

### Internal Connectivity
<TODO>

### Network Controls
<TODO>

## 3. Example

| Source | Destination | Purpose | Protocol / Port |
|--------|-------------|---------|-----------------|
| Internet | API Gateway | Client access | HTTPS 443 |
| App Services | Database | Data access | TCP 5432 |
| Site Gateway | Control Plane | Telemetry sync | HTTPS 443 |

## 4. Guidance
- Focus on architecture-level connectivity, not firewall rule micro-detail
- Important for both SaaS and OT boundary modeling