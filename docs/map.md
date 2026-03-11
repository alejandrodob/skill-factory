# Skill Factory Structure

```
skill-factory/
├── CLAUDE.md                           # Agent instructions for this project
├── update-docs                         # Bash wrapper to update documentation
├── scripts/                            # Automation scripts
│   ├── sources.txt                     # URLs to fetch docs from
│   └── fetch_anthropic_skill_docs.py   # Fetch latest Anthropic docs
├── docs/                               # All knowledge about creating skills
│   ├── knowledge/
│   │   └── anthropic-skill-docs/       # Official Anthropic skill documentation
│   │       ├── overview.md             # What skills are, why they exist, core concepts
│   │       ├── skills.md               # Implementation syntax, structure, usage patterns
│   │       └── best-practices.md       # Proven patterns, common pitfalls, guidelines
│   ├── create_new_skill-process.md     # Instructions for creating skills
│   ├── map.md                          # This file - repository structure
│   └── project.md                      # Project-specific information
└── output_skills/                      # Created skills organized by category
    ├── testing/                        # tdd, approval-tests, mutation-testing, test-desiderata
    ├── design/                         # hexagonal-architecture, modern-cli-design
    ├── practices/                      # refactoring, refinement-loop, code-simplifier, complexity-review, hamburger-method, small-safe-steps, story-splitting, thin-wrappers
    ├── ai/                             # ai-patterns, creating-process-files
    │   └── claude-code/                # creating-hooks, writing-statuslines
    └── developer-tools/                # writing-bash-scripts, using-uv, dockerfile-review
```

## Purpose

- **docs/**: Contains all instructional material the agent uses to create skills
- **output_skills/**: Stores completed skills, each in a category subfolder
- **CLAUDE.md**: Provides context to the agent about this repository's purpose
