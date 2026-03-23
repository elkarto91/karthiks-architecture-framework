# Integration Patterns Template Guide

## 1. Purpose
Documents how the solution integrates internally and externally.

## 2. Template

### Integration Inventory

| Integration | Pattern | Protocol | Direction | Sync/Async | Notes |
|-------------|---------|----------|-----------|------------|-------|
|             |         |          |           |            |       |

### Standard Patterns Used
- REST
- Event bus
- Webhook
- File exchange
- Message queue
- Batch sync
- OT gateway relay

### Error Handling Strategy
<TODO>

### Retry / Idempotency Strategy
<TODO>

## 3. Example

| Integration | Pattern | Protocol | Direction | Sync/Async |
|-------------|---------|----------|-----------|------------|
| Partner KYC Provider | API | REST | Outbound | Sync |
| Transaction State Updates | Events | Kafka | Internal | Async |

## 4. Guidance
- Include both business and technical integrations
- Very important for SaaS and OT systems