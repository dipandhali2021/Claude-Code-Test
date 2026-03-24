# CLAUDE.md

This file provides guidance for AI assistants (like Claude) working in this repository.

## Project Overview

<!-- TODO: Update with actual project description -->
This is the `claude-code-test` repository. Update this section with the project's purpose, goals, and high-level architecture as the codebase develops.

## Tech Stack

<!-- TODO: Update as technologies are adopted -->
- **Language**: TBD
- **Framework**: TBD
- **Package Manager**: TBD
- **Testing**: TBD
- **Linting/Formatting**: TBD

## Project Structure

```
.
├── CLAUDE.md          # AI assistant guidance (this file)
└── README.md          # Project documentation (to be created)
```

<!-- TODO: Update as directories are added. Example:
├── src/               # Source code
├── tests/             # Test files
├── docs/              # Documentation
├── scripts/           # Build and utility scripts
└── config/            # Configuration files
-->

## Development Setup

### Prerequisites

<!-- TODO: List required tools and versions -->
- Git

### Installation

```bash
git clone https://github.com/dipandhali2021/claude-code-test.git
cd claude-code-test
# TODO: Add install commands (e.g., npm install, pip install -r requirements.txt)
```

### Running Locally

```bash
# TODO: Add run commands
```

## Common Commands

<!-- TODO: Fill in as the project develops -->
| Command | Description |
|---------|-------------|
| `TBD`   | Build the project |
| `TBD`   | Run tests |
| `TBD`   | Lint code |
| `TBD`   | Format code |

## Code Conventions

### General

- Write clear, self-documenting code; add comments only when intent isn't obvious
- Keep functions small and focused on a single responsibility
- Prefer descriptive variable/function names over abbreviations
- Do not introduce new dependencies without justification

### File Organization

- Group related files together in directories
- Keep test files close to the code they test
- Use consistent file naming conventions across the project

### Error Handling

- Handle errors at appropriate boundaries
- Provide meaningful error messages
- Do not silently swallow errors

## Git Workflow

### Branch Naming

Use descriptive branch names with a prefix:
- `feature/` — new features
- `fix/` — bug fixes
- `refactor/` — code refactoring
- `docs/` — documentation changes
- `test/` — adding or updating tests

### Commit Messages

- Use concise, imperative mood (e.g., "Add user auth" not "Added user auth")
- Keep the subject line under 72 characters
- Add a body for non-trivial changes explaining **why**, not just **what**

### Pull Requests

- Keep PRs focused on a single change
- Include a clear description of what changed and why
- Ensure all checks pass before requesting review

## Testing

<!-- TODO: Update with actual testing approach -->
- Write tests for new functionality
- Ensure existing tests pass before pushing
- Aim for meaningful coverage, not 100% coverage for its own sake

## AI Assistant Guidelines

When working in this repository, AI assistants should:

1. **Read before writing** — always read existing code before proposing changes
2. **Follow existing patterns** — match the style and conventions already in the codebase
3. **Keep changes minimal** — only change what is necessary; avoid unrelated refactors
4. **Don't over-engineer** — prefer simple solutions; avoid abstractions for one-time use
5. **Verify changes** — run tests and linters after making changes
6. **Avoid secrets** — never commit `.env` files, API keys, or credentials
7. **Update this file** — when adding new workflows, commands, or conventions, update CLAUDE.md to keep it current
