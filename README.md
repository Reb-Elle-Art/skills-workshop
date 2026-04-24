# Skills Workshop

A public repository for testing and sharing Agent Skills. Built with the [Agent Skills format](https://agentskills.io/specification) — a standardized way to give AI agents new capabilities.

## What Are Agent Skills?

Agent Skills are modular instructions that extend what an AI agent can do. They follow a simple structure:

```
skill-name/
├── SKILL.md          # Required: metadata + instructions
├── scripts/          # Optional: executable code
├── references/       # Optional: documentation
└── assets/           # Optional: templates, resources
```

Learn more at [agentskills.io](https://agentskills.io).

## Skills Here

### brainstorm-trigger
A creative brainstorming skill that forces genuine divergence, user-driven cross-pollination, and bold amplification.

Created from [Stuart's Brainstorm Trigger pattern](https://stellartogether.ai) — refined collaboratively.

**What it does:**
- Generates 5 wildly different approaches (labeled A-E)
- User picks which approaches to combine
- Cross-pollinates only the selected directions
- User picks which combinations to amplify
- Amplifies and presents
- Supports iteration on demand

**Activation:** Say "brainstorm," "ideate," "generate ideas," or "what if we..."

## Structure

```
skills-workshop/
├── README.md
├── CONTRIBUTING.md
└── skills/
    └── brainstorm-trigger/
        └── SKILL.md
```

## License

MIT — see LICENSE file.

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) for how to add skills or improve existing ones.