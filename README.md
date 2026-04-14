# BlackRoad OS -- Monorepo (Public Mirror)

Public mirror of the BlackRoad OS monorepo. Contains the OS shell and all 17 product workspace packages.

## Structure

```
packages/
  os-shell/       -- The broadcast operating system (Cloudflare Worker)
  roadtrip/       -- Agent coordination hub
  roadie/         -- AI agent runtime
  roadview/       -- Analytics and monitoring
  backroad/       -- Content and media platform
  roadcode/       -- Code editor and dev tools
  roadwork/       -- Project management
  carkeys/        -- Authentication and identity
  roadchain/      -- Blockchain and ledger
  roadcoin/       -- Token and payments
  roadbook/       -- Documentation and knowledge base
  roadworld/      -- Metaverse and spatial
  officeroad/     -- Office and productivity suite
  carpool/        -- Collaboration and sharing
  oneway/        -- Deployment and CI/CD
  roadside/       -- Support and help desk
  blackboard/     -- Education and learning
  highway/        -- Networking and infrastructure
```

## Running the OS Shell

```
cd packages/os-shell
npm install
npm run dev
```

## Workspaces

This repo uses npm workspaces. All packages are under `packages/`.

---

Copyright 2026 BlackRoad OS, Inc. All rights reserved. Proprietary and confidential.
