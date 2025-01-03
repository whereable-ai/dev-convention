## General Naming

### Golden Rule
- A name too long is better than one that's unclear or confusing.

### Essential Guidelines
- Be Descriptive
- Avoid Ambiguity
- Make Plurals Clear
- Include Units

### Filenames
- Use `snake_case` for filenames (e.g., `general_naming.md`).
- Do not use spaces or special characters except for underscores (`_`).

### Repository Names
- Use `lower-kebab-case` for repository names (e.g., `project-name`).
- Do not use spaces or special characters except for hyphens (`-`).

## Branch Names
- Use `lower-kebab-case` for branch names.
- Use the following patterns for branch names:
  - `feature/<feature-name>` for new features (e.g., `feature/relocalization`).
  - `bugfix/<issue-description>` for bug fixes (e.g., `bugfix/deadlock-quit`).
  - `release/<version-number>` for release branches (e.g., `release/1.0.0`).
- Do not use spaces or special characters except for slashes (`/`) and hyphens (`-`).
- The default branch name should be `main`.
  >To configure Git to use main as the default branch name for new repositories, run the following command (Git Version ≥ 2.28):<br>
  >```bash
  >git config --global init.defaultBranch main
  >```
