# Aetherra Labs

We’re building **Aetherra**, an experimental cognitive operating layer for personal computers. The goal is a companion you can return to the next day and pick up where you left off. Aetherra is the persistent system. **Lyrixa** is the persona you meet in chat.

We’re currently testing how memory, reasoning, and permissions work together in supervised runs with synthetic data. Broader internal alpha use is awaiting acceptance. [Current readiness decision](https://github.com/AetherraLabs/Aetherra/blob/main/docs/ALPHA_READINESS_DECISION.md)

## What Lyrixa can remember

In a verified conversation, a tester told Lyrixa that their garden observatory was called the *Lantern Room*. After a full restart, they opened an empty chat and asked what they called the place where they watched the stars. Lyrixa retrieved the original record and answered correctly. Asked what color the door was, she said she hadn’t been told. [Read the test and follow the memory record](https://github.com/AetherraLabs/Aetherra/blob/main/docs/PERSONAL_CONTINUITY.md)

## How Aetherra works

- **Memory** stores conversation records locally. The Engine retrieves relevant records and supplies them as evidence when generating a reply.
- **Guardian and Security** govern what Aetherra can do. Guardian reviews the intent behind an action and can require approval. Security enforces the permissions.
- **Homeostasis** monitors runtime health. **Self-Improvement** proposes changes for review, and **Self-Incorporation** applies approved changes within their authorized scope.
- **Aether Script** expresses goals and workflows in `.aether` files. Agents and plugins provide specialized capabilities that workflows can use.

The project also explores memory compression through QFAC and a simulator-first quantum layer. [Quantum research and roadmap](https://github.com/AetherraLabs/Aetherra/blob/main/docs/MASTER_ROADMAP.md#quantum)

## Explore the project

- [Source code and developer quick start](https://github.com/AetherraLabs/Aetherra#quick-start)
- [Who is Aetherra?](https://github.com/AetherraLabs/Aetherra/blob/main/docs/WHO_IS_AETHERRA.md)
- [Active systems and their development status](https://github.com/AetherraLabs/Aetherra/blob/main/docs/ACTIVE_SYSTEMS.md)
- [Internal alpha operator guide](https://github.com/AetherraLabs/Aetherra/blob/main/docs/ALPHA_OPERATOR_RUNBOOK.md)
- [Aetherra website](https://aetherra.dev/)
