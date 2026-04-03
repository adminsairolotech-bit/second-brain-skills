# Second Brain Skills for Claude Code

![GitHub stars](https://img.shields.io/github/stars/adminsairolotech-bit/second-brain-skills?style=flat-square)
![GitHub license](https://img.shields.io/github/license/adminsairolotech-bit/second-brain-skills?style=flat-square)
![GitHub top language](https://img.shields.io/github/languages/top/adminsairolotech-bit/second-brain-skills?style=flat-square)

A practical collection of **Claude Skills** that turns Claude Code into a reusable “second brain” for knowledge work, content production, documentation, and brand-consistent output.

Instead of overloading context all at once, these skills use **progressive disclosure**: Claude loads detailed instructions only when needed, keeping workflows efficient while still delivering domain-specific depth.

---

## Why This Repository

Claude Code is great at coding tasks—but with the right skill system, it can also support:

- Structured knowledge capture
- Repeatable content pipelines
- Branded presentation and document generation
- SOP/runbook authoring
- Skill composition and extension

This repo provides those building blocks.

---

## Key Features

- **Progressive context loading** for lower context bloat and better focus
- **External integrations** through MCP-compatible workflows (e.g., Zapier, GitHub)
- **Video creation workflows** using Remotion + React patterns
- **Presentation generation** (slides and carousel-style outputs)
- **Documentation automation** for runbooks, SOPs, and internal guides
- **Brand and voice system generation** to keep output consistent
- **Extensible skill architecture** so you can add your own domain-specific skills

---

## Included Skill: Brand & Voice Generator

Create reusable brand and tone assets once, then apply them across all downstream skills.

### Outputs

| File | Purpose | Typical Consumers |
|------|---------|-------------------|
| `brand.json` | Colors, fonts, visual assets | Presentation/content generators |
| `config.json` | Output defaults and generation settings | Presentation/content generators |
| `brand-system.md` | Design language and visual rules | All content-producing skills |
| `tone-of-voice.md` | Writing style, personality, messaging voice | Docs, slides, social content |

**Core idea:** define voice and brand once; reuse everywhere.

---

## Getting Started

Because this repository is a skill collection (not a single runtime app), usage is based on your Claude Code setup.

### 1) Clone the repository

```bash
git clone https://github.com/adminsairolotech-bit/second-brain-skills.git
cd second-brain-skills
```

### 2) Add skills to your Claude Code environment

- Copy or reference the skill files from this repo into your Claude Code skills directory/workspace.
- Keep structure intact so related assets (brand config, voice docs, templates) remain linked.

### 3) Initialize your brand system first (recommended)

Start by running/using the **Brand & Voice Generator** skill to produce:

- `brand.json`
- `config.json`
- `brand-system.md`
- `tone-of-voice.md`

These files become your reusable source of truth for other skills.

### 4) Use skills by task type

- Documentation task → use runbook/SOP-oriented skill
- Presentation task → use PPTX/carousel-oriented skill + brand assets
- Video task → use Remotion-oriented skill
- Workflow/integration task → use MCP/integration-oriented skill

---

## Suggested Workflow

1. **Define identity** (brand + voice)
2. **Capture knowledge** (docs, procedures, playbooks)
3. **Operationalize outputs** (slides, videos, social content)
4. **Refine and extend** (add new skills for recurring workflows)

---

## Repository Structure

This repository is organized as a skill library. Depending on branch/version, you may find:

- Skill definitions/prompts
- Configuration files
- Markdown guidance and templates
- Brand/voice artifacts
- Output and integration helpers

If you are adapting this for a team, consider creating a `/skills`, `/templates`, and `/examples` convention for long-term maintainability.

---

## Contributing

Contributions are welcome, especially around:

- New skill modules
- Better prompt/instruction clarity
- MCP integration recipes
- Example workflows and sample outputs
- Brand/voice portability improvements

### How to contribute

1. Fork the repository
2. Create a feature branch  
   `git checkout -b feat/your-skill-name`
3. Commit your changes  
   `git commit -m "Add: your skill description"`
4. Push to your fork  
   `git push origin feat/your-skill-name`
5. Open a Pull Request with:
   - Problem statement
   - What your skill solves
   - Usage instructions
   - Example input/output (if applicable)

Please keep contributions focused, modular, and well-documented.

---

## License

No license file is currently defined in this repository.

Until a license is added, treat the contents as **all rights reserved by default** and do not assume permission for redistribution or commercial use.

If you are the maintainer, adding a license (e.g., MIT/Apache-2.0) is strongly recommended to clarify reuse terms.