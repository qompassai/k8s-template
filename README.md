<!-- qompassai/k8s-template/README.md -->
<!-- Replace Kubernetes, Template for Qompass AI Kubernetes projects. and k8s when you instantiate this template. -->

# Kubernetes

> Template for Qompass AI Kubernetes projects.

![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)

A Qompass AI template for Kubernetes (tool) projects — starter configs,
automation skeletons, and operational notes in the standard Qompass AI
layout.

## How to use this template

1. On GitHub, click **Use this template** → **Create a new repository**.
   ([About creating a repository from a template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template))
2. Name it after your project.
3. Replace every `{{PLACEHOLDER}}` in this README and in `CITATION.cff`,
   then delete this section.
4. Copy the starter configs into place and validate each with the command
   noted at its top (e.g. `nginx -t`, `terraform validate`).

Placeholders used in this template:

| Placeholder      | Meaning                          | Example               |
|------------------|----------------------------------|-----------------------|
| `Kubernetes`    | Project name, title case         | Kubernetes           |
| `Template for Qompass AI Kubernetes projects.`| One-line repo description        | Template for Qompass AI Kubernetes projects.       |
| `k8s`       | Lowercase, URL-safe name         | k8s              |

## Layout

```text
src/            # source: configs, scripts, automation
tests/          # validation notes (each starter names its check command)
docs/           # deep dives: setup, operations, gotchas, ecosystem map
examples/       # smallest-first runnable/usable snippets
.github/        # CI: sanity checks on every push
```

## Neovim-first

Matt builds in Neovim. His config (diver) is the primary driver here:
see [docs/NEOVIM.md](docs/NEOVIM.md) for the wiring checklist
(formatter, linter, build/test, DAP). `.nvim.lua` ships project-local
settings — it defines commands only and never runs anything by itself.

## License

This project is licensed under the [Apache License, Version 2.0](./LICENSE).

Copyright 2026 Qompass AI.
