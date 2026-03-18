# WSAI (WorkingStiff AI)

## Applied Backend and Systems Learning Project

## Overview

WorkingStiff AI is a self-directed, hands-on engineering project focused on learning how modern backend systems are designed, deployed, tested, and improved in real workflows.

The project is centered on practical experience with backend services, APIs, containerized applications, cloud-oriented deployment concepts, and AI-assisted development workflows. The goal is not to present senior-level ownership or large-scale production claims, but to demonstrate serious, project-based learning through implementation, troubleshooting, iteration, and responsible use of modern tools.

This repository reflects how I am developing as a self-taught engineer by building real systems, working through problems directly, and improving my technical judgment over time.

## Project Focus

Primary areas of focus include:

- Building and understanding backend services and API-driven workflows
- Working with containerized applications using Docker
- Running and troubleshooting services in Linux environments
- Testing and debugging REST APIs
- Learning how database-backed systems and service integrations behave in practice
- Using Git and GitHub for version control and documentation
- Applying AI development tools such as ChatGPT and Cursor to accelerate research, iteration, debugging, and documentation while keeping human judgment and accountability central to the work

## Technologies and Tools

- JavaScript / TypeScript
- Node.js
- REST APIs
- PostgreSQL
- Docker
- Linux
- Git / GitHub
- AWS fundamentals and deployment-oriented concepts
- AI-assisted development tools and large language models

## Engineering Approach

This project reflects a practical learning approach built around:

- understanding how systems fit together
- writing and refining backend logic
- diagnosing failures and isolating issues
- learning safe iteration habits
- improving documentation and maintainability
- building stronger technical judgment through direct implementation

I use AI tools as force multipliers for speed and learning, but not as substitutes for responsibility or understanding. The focus is on learning how systems behave, validating outputs, thinking through edge cases, and improving code and workflows over time.

## Scope

WorkingStiff AI is an applied learning project. It represents meaningful, hands-on engineering growth through implementation and troubleshooting, but it is not intended to overstate ownership, scale, or production responsibility.

The emphasis is on honest technical development through:
- backend and systems learning
- project-based iteration
- troubleshooting and problem isolation
- responsible AI-assisted software development

## Why This Project Exists

I created this project to learn modern software engineering in a practical way rather than only through isolated tutorials. WorkingStiff AI gives me a place to build, test, troubleshoot, and refine real workflows across backend services, infrastructure concepts, documentation, and AI-assisted tooling.

It reflects my transition into software engineering through hands-on project work and continuous improvement.

# Execution Authority Systems

Source-of-truth monorepo for three bounded entities:

- WSAI: Execution Authority System (trade workflows)
- RSO: Regulated Service Operator (compliance workflows)
- Alette: Decision Authority System (meaningful friction; decision cards)

Rules:
- Changes are made and released per-entity (wsai/, rso/, alette/).
- CI is path-scoped: entity changes must not trigger other entities.
- shared/ is for truly cross-domain primitives only (no vertical logic).

Runbooks:
- alette-runbook stays in its own repo (optional local symlink only).
