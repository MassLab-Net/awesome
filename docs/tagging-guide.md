# Tagging Guide

## Choose The Right Folder

### `lists/ai/`

Use for foundational AI resources:

- Models
- Frameworks
- Evals
- RAG

### `lists/agents/`

Use for agentic systems and resources:

- Agent skills
- Coding agents
- Agent frameworks
- Multi-agent systems

### `lists/dotnet/`

Use for .NET-focused resources:

- Libraries
- Architecture
- ABP
- AI in .NET

### `lists/ecosystem/`

Use for supporting ecosystem resources:

- Tutorials
- Benchmarks
- Tooling

## Fast Decision Rules

- If the resource is mainly about agent capabilities or orchestration, place it under `lists/agents/`
- If the resource is mainly about the .NET stack, place it under `lists/dotnet/`
- If the resource is about general models, frameworks, or evaluation, place it under `lists/ai/`
- If the resource is mainly a guide, support tool, or benchmark collection, place it under `lists/ecosystem/`

## Deduplication Rules

- Do not copy the same entry into multiple files
- Pick one primary home for each resource
- Use `Compare with` for cross-references

## Minimum Required Format

Each entry must include:

- `Link`
- `Type`
- `Why it matters`

Recommended additional fields:

- `Compare with`
- `Notes`

## When To Create A New File

Only create a new file under `lists/` when:

- There are enough entries for a clear topic split
- The file name is short, clear, and expandable
- The new file does not overlap semantically with an existing one
