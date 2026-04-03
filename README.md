# Second Brain Skills for Claude Code

![GitHub stars](https://img.shields.io/github/stars/adminsairolotech-bit/second-brain-skills?style=flat-square)
![GitHub license](https://img.shields.io/github/license/adminsairolotech-bit/second-brain-skills?style=flat-square)
![GitHub top language](https://img.shields.io/github/languages/top/adminsairolotech-bit/second-brain-skills?style=flat-square)

A curated collection of **Claude Skills** that transforms Claude Code into a practical, reusable **second brain** for research, writing, documentation, workflow automation, and brand-consistent output.

This repository is designed around **progressive disclosure**: skills load deeper instructions only when needed, reducing context overload while preserving expert-level guidance.

---

## Why this project

Claude Code is excellent at coding tasks, but with a structured skill layer it can also support high-value knowledge work:

- Capture and reuse institutional knowledge
- Standardize repeatable content workflows
- Generate presentations and communication assets
- Produce SOPs, runbooks, and internal documentation
- Maintain consistent tone, style, and visual identity

---

## Key features

- **Progressive context loading** to keep prompts focused and efficient
- **Composable skill architecture** for easy extension and customization
- **Brand & voice systems** for consistent cross-channel output
- **Documentation workflows** for SOPs, runbooks, and internal guides
- **Presentation/content generation** patterns for slides and carousels
- **Automation-friendly design** compatible with MCP-style integrations (e.g., GitHub, Zapier)
- **Knowledge-first organization** to support “second brain” workflows

---

## Repository structure

This repository is organized as a set of reusable Claude Skills and supporting assets.  
A typical skill includes:

- Instructions / prompt logic
- Optional templates and output schemas
- Reusable artifacts (e.g., config and branding files)

Example generated assets from a brand/voice workflow:

- `brand.json` — visual identity tokens (colors, typography, assets)
- `config.json` — defaults for style, output format, and generation behavior
- `voice.md` (or similar) — tone, messaging, and writing guidance

> Exact file names and folders may evolve as skills are added.

---

## Installation

### Option 1: Clone this repository
1. Clone:
   - `git clone https://github.com/adminsairolotech-bit/second-brain-skills.git`
2. Enter the directory:
   - `cd second-brain-skills`
3. Add the relevant skill files to your Claude Code skill/workspace setup.

### Option 2: Download as ZIP
1. Click **Code → Download ZIP**
2. Extract locally
3. Copy the desired skill folders into your Claude Code environment

---

## Usage

1. Choose a skill that matches your task (e.g., brand system, docs workflow, content generation).
2. Load or reference the skill in Claude Code.
3. Provide project-specific context (audience, goals, constraints, style preferences).
4. Run iteratively:
   - Generate draft output
   - Review/edit
   - Save reusable artifacts for future runs

### Suggested workflow

- Start with a **Brand & Voice** skill to establish baseline standards.
- Reuse generated assets in downstream skills (documentation, slides, content).
- Keep outputs versioned in your repo for traceability and team reuse.

---

## Contributing

Contributions are welcome. If you want to add or improve skills:

1. Fork the repository
2. Create a feature branch
3. Add/update skill files and documentation
4. Submit a pull request with:
   - What the skill does
   - Inputs/outputs
   - Example usage
   - Any dependencies or integration assumptions

### Contribution guidelines

- Keep prompts/instructions modular and readable
- Prefer explicit output schemas where possible
- Document required context and expected results
- Avoid hardcoding brand/project specifics in reusable skills

---

## Roadmap ideas

- Additional domain-specific skills (product, marketing, ops, support)
- Stronger schema validation for generated assets
- Example projects and end-to-end workflow demos
- Improved interoperability with external automation tools

---

## License

This repository currently does **not** declare a license.

If you are the maintainer, consider adding a license (e.g., MIT) to clarify usage rights for contributors and adopters.