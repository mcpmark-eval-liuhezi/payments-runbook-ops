# payments-runbook-ops

This repository is the operations runbook for **payments-api**.

payments-api is the card-authorization service that handles card authorization and settlement. This runbook is the source of truth for operating payments-api on-call: it covers the service overview, escalation policy, and alert thresholds, and it is maintained by the team through pull requests.

## Contents

- [`docs/runbook.md`](docs/runbook.md) — the payments-api operations runbook
- [Open runbook gaps](https://github.com/mcpmark-eval-liuhezi/payments-runbook-ops/issues) — tracked as issues

## Conventions

- Documentation changes land through pull requests; nothing is committed straight to `main`.
- The `runbook-check` CI workflow verifies the runbook document exists on every push and pull request.
