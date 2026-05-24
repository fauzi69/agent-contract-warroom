# Product Spec — Smart Contract War Room

## Problem

Protocol security teams need fast, explainable decisions in incident response workflows. Static dashboards are not enough; the product must show how agents reason, verify, and produce action plans.

## MVP included in this repo

- Deterministic scenario analysis.
- Multi-agent findings with confidence and severity.
- Traceable report IDs.
- API and CLI usage paths.
- CI tests that prove the reasoning shape remains stable.

## Built-in scenarios

- reentrancy alert
- oracle manipulation incident
- privileged key compromise

## Success metrics

- Report generated in under one second locally.
- Every report has findings from all specialist agents.
- Every high-risk scenario returns an operator action plan.
- Product can be demoed without private keys or paid model access.
