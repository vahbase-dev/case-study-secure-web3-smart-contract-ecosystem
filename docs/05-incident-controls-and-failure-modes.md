# 05 — Incident Controls and Failure Modes

## Goal
Limit blast radius and enable safe recovery during incidents.

## Controls
- pausable flows for critical operations
- circuit breakers for external dependencies
- capped withdrawals / rate limits (as applicable)
- emergency role with minimal scope

## Failure Modes
- oracle failure or manipulation
- bridge / dependency outage
- congestion and stuck transactions
- partial indexing outages

## Recovery
- freeze risky paths
- publish incident timeline via events/logs
- reconcile on-chain truth with off-chain projections
