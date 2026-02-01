# 04 — Events, Indexing, and Auditing

## Goal
Enable deterministic off-chain indexing and audit-friendly traceability.

## Event Design
- stable, versioned event schemas
- emit events for all state transitions
- include correlation identifiers where possible
- avoid ambiguous or overloaded events

## Indexing Principles
- replay-safe consumers
- idempotent writes using dedupe keys
- safe-block processing to handle reorgs
- materialised views for fast reads

## Auditing
- event-driven evidence trail
- periodic invariant checks and alerts
