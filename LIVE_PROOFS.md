# Finalized StudioNet proofs

Contract: https://explorer-studio.genlayer.com/address/0x3E6Ae64A651B952e330dB27dbA221084b49520FA

## Verified and activated interpretation

- Create human intent: https://explorer-studio.genlayer.com/tx/0x09b67b9f356ac2d1c5160679c99ae0873676ac0753ff5134e85e05423c2941bd
- Authenticated agent submission: https://explorer-studio.genlayer.com/tx/0x4d5543d39bd5f49f870ca09e4721738b20b499c56677d0901c17eae5a58cf261
- Consensus alignment: https://explorer-studio.genlayer.com/tx/0x555f38d3ecba5ab10e0aedeeb8943f562e376ffa393fad1e15820e0a8aa643a1
- Controller activation: https://explorer-studio.genlayer.com/tx/0xd0313147daf762ac958d7a0e194c3acfe79b8fc90a2264bbf7ae02bc93894f69

Stored vector: GOAL, CONSTRAINTS, EXCEPTIONS and CONTEXT all `PRESERVED`;
hidden-assumption risk `LOW`; decision `VERIFIED`. The revision is `ACTIVE` and
the exact interpretation-hash consumer gate returns `true`.

## Rejected interpretation

- Create human intent: https://explorer-studio.genlayer.com/tx/0xff548c1da4fe49ef5bc083cdcc10d297daa66aa9b2aa16f06c59d5296c3881db
- Authenticated agent submission: https://explorer-studio.genlayer.com/tx/0x3eaa779a3e66fd042c18c32ed84c1e0e78f62f74d4ca935c19d5a9914982e062
- Consensus rejection: https://explorer-studio.genlayer.com/tx/0x25e6ef7384d9dc53002210adcad5d1765a51cdb0679ea23e4da4905fedaf7d1e

Stored vector: every dimension `BROKEN`; hidden-assumption risk `HIGH`;
decision `MISALIGNED`. No revision became active.

All transactions finalized with `MAJORITY_AGREE`. Validators independently
fetched both public sources and exactly agreed on source status, HTTP status,
fingerprints, every categorical field, decision and vector fingerprint.
