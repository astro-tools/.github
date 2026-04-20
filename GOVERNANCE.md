# Governance

This document describes how the astro-tools organization is run. It is intentionally lightweight and will evolve as the community grows.

## Mission

astro-tools develops open-source software for astrodynamics, mission analysis, and space operations. We aim to make mission design tools more accessible, interoperable, and reproducible.

## Roles

### Users

Anyone who uses astro-tools software. Users are encouraged to report bugs, ask questions, and suggest improvements.

### Contributors

Anyone who contributes — via code, documentation, review, design, or other means. There is no formal application: open a pull request or help answer a question and you are a contributor.

### Maintainers

Contributors with commit rights on one or more repositories. Maintainers are responsible for:

- Reviewing and merging pull requests.
- Triaging issues.
- Guiding the technical direction of their repository.
- Upholding the [Code of Conduct](CODE_OF_CONDUCT.md).

New maintainers are invited by existing maintainers based on sustained, high-quality contribution and good judgment. There is no fixed threshold; invitation is by consensus of the current maintainers of the repository in question.

### Organization administrators

A small number of individuals have administrative rights over the GitHub organization itself (creating repositories, managing teams, etc.). Admins act on behalf of the community and follow the same decision-making processes as maintainers.

## Decision making

We aim for **lazy consensus**: proposals are assumed to have support unless someone objects. For most decisions, a discussion on the relevant issue or pull request is sufficient.

For decisions that affect multiple repositories or the organization as a whole (e.g. adopting a new project, changing organization-wide policies), an RFC-style discussion in this repository's [Discussions](https://github.com/orgs/astro-tools/discussions) is the norm. Anyone may open one; resolution is by rough consensus among active maintainers.

If consensus cannot be reached, organization administrators may make a final call, with reasoning recorded in the discussion.

## Adding a new repository

New repositories join the organization when:

1. They fit the organization's mission.
2. There is at least one willing maintainer.
3. They adopt the default community health files and `LICENSE` (or equivalents).

Proposals for new repositories should be opened as a Discussion before the repository is created.

## Archiving or removing a repository

Repositories that become unmaintained may be archived. Removal is reserved for exceptional cases (e.g. legal or licensing issues). Either action is discussed publicly before being taken.

## Changes to this document

This document can be changed by opening a pull request. Material changes should have broad discussion before merging.
