# Identity and Access Template Guide

## Purpose
Defines identity models and access control mechanisms.

---

## Template

### Identity Types
- End users
- Admin users
- Service accounts
- Machine identities
- Devices (OT)

### Authentication Methods
<TODO>

### Authorization Model
- RBAC / ABAC / Policy-based

### Role Definitions
<TODO>

### Access Control Matrix

| Role | Resource | Access Type |
|------|----------|-------------|
|      |          |             |

### Privileged Access Strategy
<TODO>

### Multi-Tenancy Access Model (if SaaS)
<TODO>

---

## Example

- Users authenticate via OAuth
- Services use mTLS and tokens

---

## Guidance

- Separate identity from authorization
- Always define machine-to-machine access