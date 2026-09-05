# Hubuntu Sentinel — Product Overview

Hubuntu Sentinel is a compact, local-first **network security monitor for Hubuntu Linux**.

The project is designed for two audiences at the same time:

1. everyday users who need a clear answer to **"Am I protected?"**;
2. technical users who may want deeper connection, process, risk and incident details.

## Product direction

Sentinel observes network activity, remembers what it has seen, evaluates unusual behaviour, groups related findings, applies a protection policy and presents the result in simple language.

```text
Observe → Remember → Analyze → Decide → Respond
```

## Current protection model

### Normal
Balanced everyday monitoring and protection.

### Strict
Tighter review of public, unattributed or unusual activity.

### Aggressive
Higher sensitivity for activity that deserves faster containment review.

## Simple-first console

The primary console is intentionally not designed like a SOC dashboard. Its main job is to communicate:

- Protection ON / OFF
- Safe / Needs Review / Blocked
- Low / Medium / High Risk
- Active protection profile
- recent incidents requiring attention

Advanced information remains available through detail views.

## Architecture in development

- Network observer
- Process/application attribution
- SQLite event database
- Explainable risk scoring
- Incident correlation
- Policy engine
- Response engine
- Audit trail
- Compact user console

## Technical Preview

Hubuntu Sentinel is under active development. Current functionality should be treated as a Technical Preview rather than a complete replacement for mature enterprise EDR/XDR products.

## Development model

Source development currently remains private inside Hubuntu Core. This public repository is used for product information, roadmap, project status, screenshots, licensing information and future stable releases.

## Support

[☕ Support Hubuntu Sentinel on Buy Me a Coffee](https://buymeacoffee.com/hubuntu)
