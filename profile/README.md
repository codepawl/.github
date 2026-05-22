# CodePawl

Infrastructure for autonomous coding agents.

CodePawl builds tools that help coding agents debug failures, remember useful context, coordinate work, recover from long-horizon execution errors, and optimize agent workloads.

## Stack

- **TracePawl** — failure diagnosis and replay for coding agents
- **MemPawl** — persistent memory for agentic systems
- **OpenPawl** — runtime for coordinated coding agents
- **CachePawl** — optimization for long-horizon agent workloads

## Current Focus

The current priority is **TracePawl**: a debugging and postmortem tool for coding-agent failures.

TracePawl focuses on answering questions such as:

- Why did the agent fail?
- Where did execution start to drift?
- Which tool call or context update caused the failure?
- What recovery action should be attempted next?
- Has a similar failure happened before?

## Research Direction

CodePawl is interested in four core problems:

- Why coding agents fail
- How agents remember useful operational knowledge
- How multiple agents coordinate safely
- How long-running agent execution becomes cheaper and more reliable

## Status

CodePawl is early-stage research and engineering work. APIs, architecture, and project boundaries may change quickly.

## Contact

Founder: An Nguyen  
Email: founder@codepawl.com
