# Smolnikov Research Skill - `flux-qwen-image`

> **Category:** Generative Media (On-Demand) · **License:** MIT · **Author:** [Smolnikov Research Center](https://github.com/SmolnikovResearch)

**EN:** On-demand image generation with FLUX Klein and Qwen.

**RU:** Генерация изображений и постеров через FLUX 3 Image Klein / Qwen-Image-2.1 по требованию.

---

## On-Demand Activation & Lazy Loading (`on-demand.json`)

This skill stays **disabled by default** (`auto_load_on_startup: false`) and loads dependencies/checkpoints strictly when you enable and run it:

| Component | Requirement |
|---|---|
| System binaries | `none` |
| Python packages | `torch, diffusers, transformers` |
| Model checkpoints | `Qwen/Qwen-Image` |

## Installation in CapyAgent

```bash
capyagent skills install SmolnikovResearch/flux-qwen-image/skills/flux-qwen-image
```

Or copy this directory into `~/.capyagent/skills/` (or `~/.agents/skills/`).

## Check Status & Bootstrap Dependencies

```bash
python3 scripts/optional_skill_bootstrap.py flux-qwen-image --status
python3 scripts/optional_skill_bootstrap.py flux-qwen-image --install
```

See [`SKILL.md`](SKILL.md) for agent instructions and workflow examples.

## Related

- Full multi-skill catalog: [SmolnikovResearch/skills](https://github.com/SmolnikovResearch/skills)
- License: [MIT](LICENSE)
