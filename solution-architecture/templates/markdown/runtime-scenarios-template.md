# Runtime Scenarios Template Guide

## 1. Purpose
Explains key end-to-end runtime behaviors for important use cases.

## 2. Template

### Scenario Name
<TODO>

### Trigger
<TODO>

### Preconditions
<TODO>

### Main Flow
1. Step 1
2. Step 2
3. Step 3

### Alternate / Failure Paths
<TODO>

### Outputs
<TODO>

### Observability Notes
<TODO>

## 3. Example

### Scenario Name
Execute compliant payment

### Trigger
User submits payment request

### Preconditions
User authenticated, account active

### Main Flow
1. API Gateway receives request
2. Payment Orchestrator validates format
3. Compliance Engine evaluates rules
4. Wallet Service signs transaction
5. Blockchain Connector submits transaction
6. Event emitted for settlement update

## 4. Guidance
- Cover top 3 to 7 critical scenarios
- These should map to sequence diagrams
- Include failure and retry behavior