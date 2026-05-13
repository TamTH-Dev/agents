# Agent Configuration Repository

This repository stores all personal configuration and settings for AI agents.

## Purpose
Centralized storage for AI agent personalization and capability extensions.

## Structure
- `/skills`: Store specialized agent skills (instructions and workflows).
- `/prompts`: System prompts and interaction templates.
- `/guidelines`: Repos-specific or general agent behavior standards.
- `/rules`: Specific constraints and logic rules for agent behavior.

## Workflow
- When adding new skills, ensure they follow the skill format defined in the repository's standards.
- Keep guidelines concise and high-signal to avoid context window bloat.
- After any change to the project structure (adding/removing directories or modifying core architectural files), the `AGENTS.md` and `README.md` files must be updated to reflect the current structure and purpose.
