# Second Brain Skills for Claude Code

![GitHub stars](https://img.shields.io/github/stars/adminsairolotech-bit/second-brain-skills?style=flat-square)
![GitHub license](https://img.shields.io/github/license/adminsairolotech-bit/second-brain-skills?style=flat-square)
![GitHub top language](https://img.shields.io/github/languages/top/adminsairolotech-bit/second-brain-skills?style=flat-square)

A practical collection of modular **Claude Skills** that helps turn **Claude Code** into a reusable **second brain** for research, documentation, writing, workflows, and consistent communication.

> Built around **progressive disclosure**: start with minimal context, expand only when deeper guidance is needed.

---

## Why this repository

Claude Code is excellent at implementation. This repository adds a reusable skill layer for knowledge-heavy work so you can:

- Capture and reuse organizational knowledge
- Standardize repeatable writing and documentation tasks
- Generate SOPs, runbooks, briefs, and playbooks faster
- Keep tone, style, and branding consistent across outputs
- Reduce prompt bloat with composable context modules

---

## Key Features

- **Modular skill design** for mix-and-match workflows
- **Progressive context loading** to minimize token usage
- **Documentation-first patterns** (SOPs, runbooks, internal docs)
- **Content production templates** for briefs, decks, and messaging
- **Style and brand consistency hooks** via reusable references
- **Automation-ready structure** for tool-driven pipelines (e.g., MCP-style flows)
- **Second-brain orientation** focused on retrieval, synthesis, and repeatability

---

## Repository Structure

The repository is organized as reusable skill assets. A typical skill includes:

- Instruction/prompt logic
- Optional templates or output schema
- Supporting artifacts (config, style guide, brand references)

As the library grows, each skill is intended to remain independent and composable so teams can adopt only what they need.

---

## Installation

This repository is content-first (skills/templates), so setup is lightweight.

### 1) Clone the repository

```bash
git clone https://github.com/adminsairolotech-bit/second-brain-skills.git
cd second-brain-skills
```

### 2) (Optional) Create a Python virtual environment

If you add Python utilities/scripts around these skills:

```bash
python -m venv .venv
source .venv/bin/activate   # macOS/Linux
# .venv\Scripts\activate    # Windows
```

### 3) (Optional) Install dependencies

If/when a `requirements.txt` is present:

```bash
pip install -r requirements.txt
```

---

## Usage

Use these skills as building blocks in Claude Code sessions.

### Basic workflow

1. Pick a skill relevant to your task (e.g., documentation, synthesis, brand voice).
2. Load only the minimal instructions needed.
3. Expand with related templates/artifacts as complexity increases.
4. Save refined outputs back into your internal knowledge system.

### Example prompt pattern

- **Task**: “Create an incident runbook for service outages.”
- **Load skill**: runbook/SOP module
- **Add constraints**: audience, format, tone, review checklist
- **Output**: versioned, reusable internal document

### Recommended best practices

- Start narrow; avoid loading every skill at once
- Keep organization-specific style references in one place
- Version important templates and output formats
- Review generated assets before operational use

---

## Contributing

Contributions are welcome—especially new skill modules, templates, and quality improvements.

### How to contribute

1. Fork this repository
2. Create a feature branch  
   `git checkout -b feat/your-skill-name`
3. Add or improve a skill module (include usage notes/examples)
4. Commit with clear messages  
   `git commit -m "feat: add incident postmortem skill template"`
5. Push your branch  
   `git push origin feat/your-skill-name`
6. Open a Pull Request with:
   - Problem statement
   - What was added/changed
   - Example input/output
   - Any migration or compatibility notes

### Contribution guidelines

- Keep skills modular and composable
- Prefer concise, testable instructions over long monolithic prompts
- Include examples where possible
- Preserve clarity, consistency, and practical usability

---

## License

This repository currently does **not** define a license.

Until a license is added, all rights are reserved by default and reuse may be restricted.  
If you are the maintainer, consider adding an open-source license (e.g., MIT) for clarity.