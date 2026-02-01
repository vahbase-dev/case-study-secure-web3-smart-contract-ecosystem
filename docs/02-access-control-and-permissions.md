# 02 — Access Control and Permissions

## Goal
Enforce least-privilege access with clear role separation and auditable actions.

## Role Separation (Conceptual)
- admin (governance)
- operator (limited ops)
- pauser (emergency)
- upgrader (upgrade-only)
- treasury (fund custody)

## Controls
- role-based access checks
- timelocks for sensitive changes (where applicable)
- explicit allowlists for critical functions
- event emission for privileged actions

## Safety Rules
- no single role should control all critical paths
- actions must be traceable via events
