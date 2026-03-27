# CLAUDE.md

## Project Overview

Isaac Harness is a harness system for:
1. Creating new NVIDIA Isaac Sim extensions from templates
2. Adding new features to existing Isaac Sim extensions
3. Fixing bugs in existing Isaac Sim extensions

## Key Concepts

- **Extension**: An Isaac Sim extension (Omniverse Kit extension) with standard structure including `extension.toml`, Python source, tests, etc.
- **Feature**: A discrete unit of functionality that can be added to an existing extension (e.g., a new UI panel, a new action graph node, a new service).
- **Bug fix**: A targeted change to diagnose and resolve defects in an existing extension.
- **Template**: Reusable scaffolding for extensions and features.

## Development Guidelines

- Follow NVIDIA Isaac Sim / Omniverse Kit extension conventions
- Extensions use the `omni.isaac.*` namespace by default
- Python code follows PEP 8
