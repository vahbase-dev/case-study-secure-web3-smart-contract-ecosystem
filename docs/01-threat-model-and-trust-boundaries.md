# 01 — Threat Model and Trust Boundaries

## Goal
Define threats, attacker capabilities, and trust boundaries across contracts, keys, and off-chain services.

## Threat Classes (Conceptual)
- key compromise (admin, operator, deployer)
- reentrancy and callback abuse
- oracle manipulation and stale data
- replay and signature misuse
- upgrade abuse and storage collisions
- MEV and transaction ordering effects

## Trust Boundaries
- EOAs vs contract accounts
- privileged roles vs public users
- off-chain services vs on-chain truth
- external dependencies (oracles, bridges)

## Security Posture
- minimise privilege
- explicit invariant checks
- deterministic, event-driven settlement signals
