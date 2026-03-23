# Resilience and Disaster Recovery Template Guide

## 1. Purpose
Defines how the platform handles failure, recovery, continuity, and disaster scenarios.

## 2. Template

### Availability Targets
- <Target 1>
- <Target 2>

### Recovery Targets
- RTO: <Target>
- RPO: <Target>

### Failure Scenarios
| Scenario | Impact | Mitigation | Residual Risk |
|----------|--------|------------|---------------|
|          |        |            |               |

### HA Strategy
<TODO>

### DR Strategy
<TODO>

### Backup / Restore Notes
<TODO>

### Operational Recovery Steps
<TODO>

## 3. Example

### Recovery Targets
- RTO: 2 hours
- RPO: 15 minutes

### Failure Scenarios
| Scenario | Impact | Mitigation |
|----------|--------|------------|
| Region outage | Partial service disruption | Secondary region failover |

## 4. Guidance
- Be explicit about what is and is not covered
- OT and edge systems may require degraded/offline modes, not only failover