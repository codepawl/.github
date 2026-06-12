# CodePawl

**CodePawl makes coding agents work together.**

We build coordination infrastructure for coding agents: reviewable plans, guarded changes, traceable evidence, memory, replay, and cloud workflows.

Our first public product is **Openpawl**, an open runtime for coding-agent coordination. It starts in GitHub Actions and turns agent work into plans, validations, evidence bundles, and safety-gated changes.

## Stack

* **[Openpawl](https://github.com/codepawl/openpawl)** — open runtime for coordinated coding agents
* **TracePawl** — failure diagnosis, replay, and postmortems for agent runs
* **Mempawl** — persistent operational memory for agentic systems
* **CachePawl** — optimization for long-horizon agent workloads

## Current Focus

The current priority is **Openpawl**: a public GitHub Action and local runtime for reviewable coding-agent workflows.

Openpawl focuses on questions such as:

* What did the agent plan?
* Which files and context did it use?
* What validation ran?
* What changed, if anything?
* Can humans and other agents trust the run evidence?

## Research Direction

CodePawl is interested in four core problems:

* How coding agents coordinate safely
* Why long-running agent work fails
* How agents preserve useful operational memory
* How agent workloads become cheaper, faster, and more reliable

## Status

CodePawl is early-stage research and engineering work. APIs, architecture, and product boundaries may change quickly.

## Contact

Founder: An Nguyen
Email: [founder@codepawl.com](mailto:founder@codepawl.com)
Website: https://codepawl.com
