# The Living Layer

**An architecture thesis: sandboxes for execution, governed state for context.**

A speculative essay about agent-native software. It asks what happens when execution history, policy, UI definitions, and data share one queryable substrate. This repository publishes the essay and an interactive thinking tool; it does not ship that platform.

[Read the essay](https://zozo123.github.io/the-living-layer/) · [Yossi Eliaz](https://github.com/zozo123)

## The proposal

- **Sandbox:** scoped, observable execution for agent-authored work.
- **Substrate:** versioned data, policy, agent contracts, and history.
- **Projection:** views over that state for people and agents.

The essay argues for this direction. Its unified architecture and dated scenarios are hypotheses, not measured outcomes or a delivery roadmap.

## Evidence and references

- **My writing:** [The Sandbox Shift](https://zozo123.github.io/sandboxes-why-how-when/) and [Databases in the Age of AI](https://zozo123.github.io/databases-in-the-ai-era/).
- **My prototype:** [Agentic Airbyte](https://github.com/zozo123/agentic-airbyte), a sandboxed data-movement POC with a published run receipt and explicit scope. It is one experiment, not the complete Living Layer.
- **Existing upstream software:** [Crabbox](https://github.com/openclaw/crabbox), [Conductor](https://github.com/conductor-oss/conductor), [Harbor](https://github.com/harbor-framework/harbor), [DeepAgents](https://github.com/langchain-ai/deepagents), and [Odysseus](https://github.com/arcahyadi/odysseus). Repositories with these names in my account are forks. Original authorship belongs to those upstream projects.

## Local preview

```bash
python3 -m http.server 8787
# open http://localhost:8787/
```

The site is a single `index.html` served by GitHub Pages, with `.nojekyll`.

## License / use

CC BY 4.0. Fork it, critique it, test the assumptions.

Yossi Eliaz · 2026
