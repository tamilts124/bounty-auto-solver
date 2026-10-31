# Bounty Auto Solver Runner

Autonomous GitHub Actions orchestrator for resolving GitHub bounties.

## Architecture
- Runs on GitHub Actions Windows/Linux runners.
- Discovers live bounties backed by Algora and Polar.sh.
- Spawns isolated sandboxes to reproduce bugs, implement fixes, and run regression tests.
- Submits verified Pull Requests automatically.
