# Memory Model Template Guide

## 1. Purpose
Defines what the agent remembers, for how long, and under what controls.

## 2. Template

### Memory Types
- Session memory
- Task memory
- User preference memory
- Project memory
- Enterprise knowledge memory

### Memory Scope
<TODO>

### Persistence Rules
<TODO>

### Expiry / Retention Rules
<TODO>

### Write Conditions
<TODO>

### Read Conditions
<TODO>

### Privacy / Compliance Constraints
<TODO>

### Memory Risks
<TODO>

## 3. Example

### Memory Types
- Session memory for current conversation
- Project memory for approved architecture facts
- No persistent storage of sensitive customer secrets

## 4. Guidance
- Separate transient reasoning context from persistent memory
- Never make memory implicit; define it explicitly
- This is critical for trust and compliance