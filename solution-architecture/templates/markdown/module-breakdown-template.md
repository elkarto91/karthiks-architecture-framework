# Module Breakdown Template Guide

## 1. Purpose
Breaks the solution into internal modules or bounded contexts for implementation clarity.

## 2. Template

### Module Name
- Responsibility
- Key Interfaces
- Dependencies
- Owned Data
- Notes

## 3. Example

### Wallet Module
- Responsibility: Create and manage wallets
- Key Interfaces: Wallet API, signing API
- Dependencies: KMS, blockchain connectors
- Owned Data: Wallet metadata

## 4. Guidance
- Use this when solution size is non-trivial
- Good place to reflect domain-driven boundaries