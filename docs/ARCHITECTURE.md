# Smart Contract War Room Architecture

## Purpose

Incident command product for exploit triage, blast-radius mapping, patch planning, and stakeholder updates.

## Runtime loop

1. **Observe** — collect domain signals: at_risk_tvl, exploit_confidence, affected_functions, pause_window_minutes, patch_complexity.
2. **Orient** — map the active scenario to specialist agent responsibilities.
3. **Decide** — score severity, confidence, and operator urgency.
4. **Act** — emit next actions that a human operator can verify.
5. **Reflect** — attach trace IDs and deterministic evidence for review.

## Components

- `backend/swarm.py` — pure Python reasoning core, safe for CI and static demos.
- `backend/app.py` — FastAPI wrapper for product integration.
- `cli.py` — terminal demo path for reviewers.
- `index.html` — front-facing dashboard surface.

## Agent responsibilities

- `Exploit Triage Lead`: owns one part of the analysis loop.
- `Blast Radius Mapper`: owns one part of the analysis loop.
- `Patch Strategy Agent`: owns one part of the analysis loop.
- `Comms Liaison`: owns one part of the analysis loop.
- `Postmortem Analyst`: owns one part of the analysis loop.

## Production extension points

- Replace deterministic signals with live connectors.
- Persist reports in Postgres or SQLite.
- Add auth and organization workspaces.
- Add export hooks for Slack, Discord, Telegram, or email.
