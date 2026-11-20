# Git Workflow

## Branch Strategy

main
Production-ready branch.

develop
Integration branch.

feature/*
Feature development branches.

bugfix/*
Bug fixing branches.

hotfix/*
Emergency production fixes.

## Workflow

feature/*
    ↓
Pull Request
    ↓
develop
    ↓
Pull Request
    ↓
main

## Rules

- No direct push on main.
- Pull Requests are required for merging into main.
- Force pushes are prohibited.
- Branch deletion is restricted.
- Conventional Commits are required.
- Documentation must be updated when necessary.