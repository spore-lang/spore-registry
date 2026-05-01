# Spore Registry

This repository is a placeholder and bootstrap area for the future Spore
registry. It is not a live public package registry.

## Current status

The repository currently contains release and contribution hygiene for future
registry work, including:

- a pull request template that defines the expected review sections;
- a pull request check workflow that validates PR title and body shape.

These files help keep early registry changes reviewable while the registry
design and implementation are still being developed.

## Not available yet

Public package registry workflows are not available from this repository yet.
In particular, the repository does not currently provide:

- package publishing;
- package installation;
- package lockfile generation or validation;
- content-addressed package store workflows;
- registry discovery or resolution APIs.

Content-addressed package workflows are on the roadmap for the Spore registry,
but they are not implemented or available for public use yet.

## Intended use

For now, treat this repository as public project scaffolding for the future
registry. Do not rely on it as a production package registry, package index, or
source of installable Spore packages.
