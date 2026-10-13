<p align="center">
  <img src="https://raw.githubusercontent.com/kaimahi-agents/kaimahi/main/brand/hero.png"
       alt="Kaimahi night worker guarding paths for AI agents"
       width="100%">
</p>

# Kaimahi

**Build, evaluate and ship AI agents on Kubernetes.**

kmx is an open-source CLI for the agent lifecycle: author agents in a Git workspace, evaluate them against real cases, publish them as versioned [AgentSuites](https://github.com/kaimahi-agents/kaimahi/blob/main/agentsuite/spec.md), and lift an exact evaluated version onto a cluster. It works with Orka and kagent today, and uses agentsessions for recorded, replayable evaluation.

## Start here

- **[Install and quickstart](https://github.com/kaimahi-agents/kaimahi/blob/main/docs/getting-started.md)**
- [Workspaces: create, eval, push, lift](https://github.com/kaimahi-agents/kaimahi/blob/main/docs/suite-workspace.md)
- [Contribute](https://github.com/kaimahi-agents/.github/blob/main/CONTRIBUTING.md) · [Report a security issue](https://github.com/kaimahi-agents/kaimahi/security/advisories/new)

## Repositories

- [kaimahi](https://github.com/kaimahi-agents/kaimahi): the kmx CLI and the AgentSuite spec
- [agents](https://github.com/kaimahi-agents/agents): example agents and their evaluation gates
- [homebrew-tap](https://github.com/kaimahi-agents/homebrew-tap): `brew install kaimahi-agents/tap/kmx`
