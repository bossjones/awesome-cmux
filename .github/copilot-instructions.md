# Copilot instructions

## Repository model

This repository is a curated guide to the cmux ecosystem, not the cmux application. `README.md` is the primary deliverable and the source of the project inventory. The `docs/` tree contains user and integration references; `scripts/update_stars.py` parses repository links from the README and updates their star counts.

The README presents the same projects through two intentionally overlapping indexes: ten feature dimensions and a secondary “By Agent” index. When adding or changing an entry, preserve this matrix: include it in every relevant feature section and its appropriate agent section. The table layout is also consumed by the star updater, which expects repository rows in Markdown tables and the star count in the final cell.

## Contribution conventions

Before editing the README, follow the authoritative structure, classification, research, and ordering rules in [`AGENTS.md`](../AGENTS.md), and the inclusion criteria and contributor checklist in [`CONTRIBUTING.md`](../CONTRIBUTING.md). In particular, verify that a candidate uses a cmux API, use only the approved tags, and write a distinct 30–50 word description that starts with a verb.

For changes to `docs/sidebar-integration-api.md`, verify protocol claims against actual integration sources rather than inferring details. Keep the existing README navigation and matrix intact.

## Build, test, and lint

No project build, test suite, or lint command is configured in this repository. There is no single-test command.
