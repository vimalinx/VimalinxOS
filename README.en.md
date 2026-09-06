# VimalinxOS

**Give AI the capabilities to get work done on your own computer.**

An open-source Linux work environment and infrastructure for humans and AI agents.

[简体中文](README.md) · [English](README.en.md)

VimalinxOS aims to make a computer an environment agents can understand and operate. You provide a goal; an agent discovers capabilities, uses models and tools, operates applications, checks results, and diagnoses and recovers from errors.

This repository is the public overview and navigation hub. Its components are developed, released, and maintained independently. The overall vision does not imply that a unified installation image or complete end-to-end integration has already shipped.

## Open-source projects

These nine repositories were verified as public, non-fork repositories on **2026-09-06**. Consult each project's documentation and release notes for supported features, platforms, installation, and release status.

| Project | Role | Repository |
| --- | --- | --- |
| **LocalRouter** | Local gateway for model APIs, service interfaces, caller identities, and agent capability discovery. | [LocalRouter](https://github.com/vimalinx/LocalRouter) |
| **Shuheng / 枢衡** | Terminal control surface for local agent sessions, execution, scheduling, and ongoing work. | [Shuheng](https://github.com/vimalinx/Shuheng) |
| **AgentSeat** | App-scoped observation and private input for an agent, preserving the human's pointer, keyboard, host focus, and clipboard. | [AgentSeat](https://github.com/vimalinx/AgentSeat) |
| **AgentBrowser** | Owner-isolated lifecycle management for real browsers, including launch, reuse, cleanup, and optional remote connections. | [vimalinx-agent-browser](https://github.com/vimalinx/vimalinx-agent-browser) |
| **Vibe Desktop** | A local web desktop and WebApp manager for organizing and running applications on your machine. | [vibedesktop](https://github.com/vimalinx/vibedesktop) |
| **Vimalinx AI OS** | System composition and distribution control plane around component inventories, health checks, and versioned Arch Linux / Hyprland releases. | [vimalinx-ai-os](https://github.com/vimalinx/vimalinx-ai-os) |
| **All2Linux / Universal Linux Port** | Agent Skill, HAI-App contract, and reference application for porting or reconstructing software as human- and agent-native Linux applications. | [universal-linux-port](https://github.com/vimalinx/universal-linux-port) |
| **AI Workspace Template** | Durable workspace state, evidence, decisions, and handoffs so agents can continue work across sessions. | [ai-workspace-template](https://github.com/vimalinx/ai-workspace-template) |
| **HyprFlux** | Arch Linux and Hyprland desktop bootstrap, hardware profiles, and modular configuration overlays. | [HyprFlux](https://github.com/vimalinx/HyprFlux) |

The machine-readable catalog is [projects.json](projects.json). Each project retains its own license; consult the corresponding repository for its terms.

## Shared direction

- **Discoverable capabilities:** agents can inspect available operations and their limits.
- **Explicit operation surfaces:** services, terminals, browsers, and applications expose ways to act.
- **Verification and recovery:** results and evidence support diagnosis, retries, and rollback where implemented.
- **Continuity:** important state and outputs survive a single agent session.
- **Human control:** components define their own permission, input, and resource boundaries.

These are shared design goals. Actual guarantees belong to each component's implemented contract.

## Start with a component

Choose the project that addresses your immediate need: LocalRouter for API access; AgentSeat for GUI operation; AgentBrowser for browser ownership; Shuheng for agent sessions; Vibe Desktop for local WebApps; AI Workspace Template for ongoing project work; All2Linux for application adaptation; or Vimalinx AI OS and HyprFlux for system composition and desktop setup.

Public releases and ongoing development may be at different stages. Follow the documentation for the version you choose. Requirements for model services, accounts, and hardware are documented by each component.

## Contributing

Use [this repository's issues](https://github.com/vimalinx/VimalinxOS/issues) for overview corrections, project links, and discussions of the overall direction. File component bugs, feature requests, and code contributions in the relevant repository.

Maintained by [Vimalinx](https://github.com/vimalinx).
