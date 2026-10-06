# Git Workflow Documentation

## Main Branch

The `main` branch contains the stable version of the project.

## Dev Branch

The `dev` branch is used for integration and testing.

## Feature Branch

Feature branches are created from `dev` for individual changes.

Example:

feature/project-setup

## Pull Request

A Pull Request is used to review and merge changes from a feature branch into `dev`.

## Git Tags

Git tags are used to mark important versions.

Example:

v1.0.0

## Workflow

main
↓
dev
↓
feature/project-setup
↓
Pull Request
↓
dev
↓
Pull Request
↓
main
