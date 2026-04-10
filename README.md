# ChainEco-Flow

Centralized GitHub Actions workflows for ecosystem automation.

## Active workflow

- `chainstamp-npm-pulse.yml`
  - Runs npm package verification/install cycles for the Chainstamp ecosystem package list.
  - Triggers: `schedule`, `workflow_dispatch`, and `repository_dispatch` (`chainstamp_pulse`).

## Goal

Keep npm pulse/download maintenance workflows out of the package repository UI (for example `chainstamp-sdk`) and run them from this dedicated automation repository.
