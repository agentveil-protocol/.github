# AgentVeil Labs

Action-control infrastructure for autonomous agent systems.

AgentVeil helps teams inspect what agents can do before deployment, gate risky actions before execution, and produce signed evidence after execution.

## Public projects

- [AgentVeil SDK](https://github.com/agentveil-protocol/agentveil-sdk) - Python SDK for posture checks, runtime gates, signed receipts, reputation signals, and verifiable execution evidence.
- [Lurkr](https://github.com/agentveil-protocol/lurkr) - local-only scanner for risky AI-agent capability surfaces before deployment.
- [Paperclip AVP Plugin](https://github.com/agentveil-protocol/paperclip-plugin-avp) - trust and reputation tools for Paperclip agent teams.

## Core concepts

- Capability scanning before deployment.
- Runtime gates before high-risk actions.
- Signed receipts after execution.
- Reputation-aware trust signals for agent delegation.
- Verifiable credentials, DIDs, and portable evidence where useful.

## Research

- [Why AI Agent Reputation Needs Both Link Analysis and Flow-Based Gating](https://doi.org/10.5281/zenodo.19730525) - position paper on reputation and Sybil-resistance composition for open AI-agent networks.

## Install

```bash
pip install agentveil
```

Lurkr can be used as a local CLI and in GitHub Actions:

- [Lurkr repository](https://github.com/agentveil-protocol/lurkr)
- [Lurkr GitHub Action](https://github.com/marketplace/actions/lurkr-agent-capability-scanner)

## Contact

- Website: [agentveil.dev](https://agentveil.dev)
- Email: [ob@agentveil.dev](mailto:ob@agentveil.dev)
