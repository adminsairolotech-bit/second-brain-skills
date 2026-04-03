# Second Brain Skills for Claude Code

![GitHub stars](https://img.shields.io/github/stars/adminsairolotech-bit/second-brain-skills?style=flat-square)
![GitHub license](https://img.shields.io/github/license/adminsairolotech-bit/second-brain-skills?style=flat-square)
![GitHub top language](https://img.shields.io/github/languages/top/adminsairolotech-bit/second-brain-skills?style=flat-square)

A curated collection of **Claude Skills** that helps turn **Claude Code** into a practical, reusable **second brain** for research, writing, documentation, automation, and brand-consistent output.

> This project is organized around **progressive disclosure**: load only the guidance needed for the current task, then expand when deeper context is required.

---

## Why this project

Claude Code is excellent at technical execution. With a structured skill layer, it can also support high-value knowledge work:

- Capture and reuse institutional knowledge
- Standardize recurring content workflows
- Generate SOPs, runbooks, and internal documentation
- Produce presentation-ready communication assets
- Maintain consistent tone, voice, and style across outputs

---

## Key Features

- **Progressive context loading** to reduce prompt bloat and token waste
- **Composable skill modules** for flexible extension and reuse
- **Documentation workflows** for SOPs, runbooks, and playbooks
- **Content generation patterns** for briefs, decks, and social assets
- **Brand and voice consistency** via reusable style references
- **Automation-friendly structure** for MCP-style integrations (e.g., GitHub, Zapier)
- **Second-brain orientation** focused on retrieval, synthesis, and repeatability

---

## Repository Structure

This repository is organized as reusable skill assets.  
A typical skill includes:

- Instruction/prompt logic
- Optional templates and output schema
- Reusable artifacts (e.g., config, style, branding files)

As the library grows, expect skills to remain modular so you can adopt only what your workflow needs.

---

## Installation

> Current repository state may be early-stage. If folder names differ, adapt examples below to actual paths.

### 1) Clone the repository

```bash
git clone https://github.com/adminsairolotech-bit/second-brain-skills.git
cd second-brain-skills
```

### 2) (Optional) Create a Python virtual environment

```bash
python -m venv .venv
source .venv/bin/activate   # macOS/Linux
# .venv\Scripts\activate    # Windows PowerShell
```

### 3) (Optional) Install dependencies

If a `requirements.txt` or `pyproject.toml` is present:

```bash
pip install -r requirements.txt
```

---

## Usage

Because this repo is a **skill collection**, usage typically follows one of these patterns:

### A) Copy skill prompts/templates into your Claude Code workflow
- Select a skill folder
- Reuse/adapt its instructions
- Add project-specific constraints and desired output format

### B) Reference skills as modular “building blocks”
- Start with a lightweight base skill
- Layer in deeper context only when needed
- Combine multiple skills for complex workflows (e.g., research → outline → final draft)

### C) Integrate into automation pipelines
- Use skill outputs as structured handoffs
- Connect with MCP tools or external automation platforms
- Keep brand/voice config centralized for consistency

---

## Example Workflow

1. Choose a task (e.g., “Create incident-response runbook”)
2. Load the relevant documentation skill
3. Provide organizational context, constraints, and audience
4. Generate draft output
5. Apply style/brand skill for final polish
6. Save artifact back to your knowledge base

---

## Contributing

Contributions are welcome. Suggested contributions include:

- New skills for repeatable workflows
- Better templates and schema definitions
- Improvements to prompt clarity and modularity
- Real-world usage examples and documentation

### How to contribute

1. Fork the repository
2. Create a feature branch  
   `git checkout -b feat/my-skill`
3. Add/update skill files and docs
4. Commit changes  
   `git commit -m "Add: <short description>"`
5. Push branch  
   `git push origin feat/my-skill`
6. Open a Pull Request with:
   - What problem this solves
   - Expected inputs/outputs
   - Example usage

---

## License

No license is currently defined in this repository.

Until a license is added, treat all rights as reserved by default.  
If you are the maintainer, consider adding an OSS license (e.g., MIT) to clarify reuse permissions.