# THE LIVING LAYER

**Sandboxes. State. One Substrate.**

A single-file, high-signal vision document for the AI era of software.

- Live: https://zozo123.github.io/the-living-layer/
- Source: this repo (one `index.html` + `.nojekyll`)

## Philosophy

When the primary author of code is a model and the primary reader of data is an agent, the old stack (frontend repo, backend repo, database, auth, deploy pipeline) becomes a liability surface.

Two new primitives dominate:

1. **The Sandbox** — the only safe place to let non-human authors execute. Disposable, observable, killable computers with explicit scopes.
2. **The Substrate** — one living database that contains not only facts, but UI definitions, agent contracts, sandbox blueprints, permissions, full causal history, and policy. The schema *is* the application.

UI becomes a projection. Logic becomes governed execution attached to that substrate. "Deploy" becomes instantiation of a sandbox with a view.

This is not marketing. It is the logical destination of the physics already visible in 2026.

## Related work by the same author

- [The Sandbox Shift](https://zozo123.github.io/sandboxes-why-how-when/) — field manual + interactive decider
- [Databases in the Age of AI](https://zozo123.github.io/databases-in-the-ai-era/) — full course + essays on the database as agent substrate
- [Crabbox](https://github.com/zozo123/crabbox), [Conductor](https://github.com/zozo123/conductor), [Harbor](https://github.com/zozo123/harbor), [DeepAgents](https://github.com/zozo123/deepagents) and others — real artifacts building pieces of the layer today

## How to view locally

```bash
python3 -m http.server 8787
# open http://localhost:8787
```

## Deploy

This repo is configured for GitHub Pages (root, no Jekyll).

## License / use

Fork it. Critique it. Help make the layer real. CC BY 4.0 or just be excellent.

— Yossi Eliaz (zozo123), 2026
