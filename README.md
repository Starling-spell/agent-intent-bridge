# AgentIntentBridge

AgentIntentBridge is a reusable GenLayer primitive that verifies whether an authenticated agent interpretation preserves a human controller's intent before an execution scope becomes active.

Validators independently fetch the bound intent context and interpretation evidence, reconstruct an exact categorical vector for goal, constraints, exceptions and context, classify hidden-assumption risk, and require exact equality of the complete report. The decision is derived deterministically; no free-form summary, numeric tolerance or leader-supplied decision controls state.

## Invariants

- Only the registered agent can submit an interpretation.
- Only the human controller can activate or revoke a verified scope.
- Revision IDs are reserved on submission and cannot be reused.
- Broken meaning or high hidden-assumption risk is `MISALIGNED`.
- Partial, unknown or unavailable evidence is `INDETERMINATE`, never verified.
- Consumer gates bind the active revision and exact interpretation hash.
- An active scope cannot be silently replaced.
