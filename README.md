# grimreach_docs

Master documentation for the Grimreach architectural workspace.

See also: [Grimreach Design & Architecture](./README.md) (This file)

## Core Responsibilities
- Master documentation for Grimreach architecture
- Defines deterministic systems and design philosophy
- Describes project layout and phase structure
- Contains no runtime code

## Architectural Role
Serves as the central knowledge base for the entire Grimreach project. It holds the "Brain" of the project, including agent instructions, phase definitions, and high-level architectural decisions that span across multiple repositories.

## Deterministic Contract Surface
- Agent Instructions (Txt/Markdown)
- Phase Definitions

## Explicit Non-Responsibilities
- No runtime code
- No binary assets
- No implementation logic

## Folder/Layout Summary
- `agent_instructions/`: Phase-by-phase detailed instructions for AI agents.
- `design/`: High-level design documents (if any).

## Development Notes
This repository is text-only. It requires no build system, no compiler, and no dependencies other than a text editor or markdown viewer.