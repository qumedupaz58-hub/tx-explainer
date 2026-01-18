# tx-explainer
# tx-explainer

Experimental EVM-based application that helps users understand
what they are actually signing before sending a transaction.

## What it does
- Simulates transactions before signing
- Decodes calldata into human-readable actions
- Highlights risky patterns (blind signing, infinite approvals, unexpected transfers)

## Why
Blind signing is still one of the biggest UX and security issues in Web3.
The goal of this project is to make transaction intent explicit and understandable.

## Experimental build
An early experimental build is available under `/Builds`.

The build is provided for local experimentation only.
It does not install anything system-wide and does not run background processes.
Feel free to inspect the contents before running anything.

## Status
Early-stage. Focused on validating core ideas and UX.
Improve README


