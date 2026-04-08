# kiro-agents

A repository containing custom agents for use with Kiro CLI.

## Agents

- **default** — A minimal general-purpose agent that answers questions and helps troubleshoot a broad range of issues.
- **coder** — A specialized software development agent focused on writing, debugging, and optimizing code.
- **researcher** — A research specialist that performs web-based and file-based investigations to produce guided, specific answers for research tasks.

## Steering

- **update-readme** — Ensures all workspace changes are documented in this README.

## Prompts

- **researcher** — System prompt for the researcher agent, referenced via `@researcher`.

## Project Structure

```
.kiro/
├── agents/
│   ├── default.json
│   ├── coder.json
│   └── researcher.json
├── prompts/
│   └── researcher.md
└── steering/
    └── update-readme.md
```
