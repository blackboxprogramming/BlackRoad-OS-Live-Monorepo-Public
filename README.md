# BlackRoad OS -- Monorepo (Public Mirror)

This repository is the public-safe mirror of the BlackRoad OS live monorepo.

## Role

`BlackRoad-OS-Live-Monorepo-Public` should publish the curated, sanitized subset of the private monorepo that is safe to expose publicly. It exists to share selected apps, packages, docs, examples, and public product surfaces without exposing private operations or internal control-plane details.

## What Belongs Here

- public-safe `apps/` and packages mirrored from the private monorepo
- public documentation, examples, and SDK surfaces
- brand-safe versions of the product and domain model
- open integration examples that do not expose secrets, internal hosts, or private workflows

## Shared Four-Repo Split

- `BlackRoad-OS-Live-Monorepo-Private` = canonical brain
- `BlackRoad-OS-Live-Working-Version-Private` = live proving ground
- `BlackRoad-OS-Live-Monorepo-Public` = curated public mirror
- `BlackRoad-OS-Live-Working-Version-Public` = polished public live/demo surface

## Publishing Rule

`private = truth` and `public = curated projection`

The private monorepo drives the source-of-truth registry, schemas, and internal app surfaces. This public mirror should be updated from that source with a deliberate public-safe filter.

## Mirror Priorities

1. Mirror public-safe docs and selected packages.
2. Mirror polished product shells that are ready for public view.
3. Keep examples and references aligned with the private monorepo structure.
4. Avoid leaking secrets, internal domains, private agents, or operator-only routes.

---

Copyright 2026 BlackRoad OS, Inc. All rights reserved. Proprietary and confidential.
