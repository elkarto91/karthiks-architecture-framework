# Guardrails Template Guide

## 1. Purpose
Defines policy, safety, validation, and control mechanisms that govern agent behavior.

## 2. Template

### Safety Objectives
<TODO>

### Guardrail Categories
- Input validation
- Output validation
- Policy enforcement
- Tool-use restrictions
- Data access restrictions
- Human approval gates
- Audit logging

### Restricted Topics / Actions
<TODO>

### Policy Enforcement Model
<TODO>

### Validation Checks
<TODO>

### Escalation Rules
<TODO>

## 3. Example

### Guardrail Categories
- Block secrets exposure
- Prevent configuration changes without approval
- Require citations for architecture assertions
- Restrict access to production credentials

## 4. Guidance
- Guardrails should be layered, not single-point
- Put policy in architecture, not just prompts