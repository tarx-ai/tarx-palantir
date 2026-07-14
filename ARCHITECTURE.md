# Architecture — tarx-palantir Beachhead

## Sovereign Unit Model
A **sovereign unit** is a node (EDGE or RACK) running TARX-OS with:
- Local-first runtime + bridge infrastructure (public surface only)
- Open Enterprise/Government weights path
- Closed human/local weights under user control
- Health schema + OpenAI-compatible hop (port 11435)
- Governance-friendly audit hooks

## Apollo-class Lifecycle (Conceptual Only)
We use “Apollo-class” language for autonomous deployment & lifecycle thinking.  
**No live Palantir Apollo API. No partnership claim.**  
TARX provides the open, zero-lock-in runtime layer that can sit under an existing control plane.

## Public Surface vs Control Plane
| Layer                    | Status     | Notes |
|--------------------------|------------|-------|
| Weights policy           | OPEN       | tarx-weights |
| Palantir beachhead + hop | OPEN       | This repo + connector |
| Health / canary schema   | OPEN-SOON  | Public contract |
| MCP tool contracts       | OPEN       | — |
| Full bridge impl         | CLOSED     | Health schema only |
| Cognitive engine         | CLOSED     | — |
| Memory store             | NEVER      | — |
| Supercomputer routing    | NEVER      | — |

## Anti-claims
- Not a Foundry / Apollo / AIP clone
- Not an official Palantir or NVIDIA product
- Not exposing private routing or human weights
- Complementary open layer only

## Thesis
**Apollo-class lifecycle. TARX-class sovereignty.**  
Manage the fleet your way — own the runtime and weights.

## Related
- Connector: https://github.com/tarx-ai/tarx-palantir-connector
- Weights: https://github.com/tarx-ai/tarx-weights
