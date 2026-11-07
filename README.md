# Oppia

This repository contains a development copy of [Oppia](https://www.oppia.org/), an open-source platform for creating and sharing interactive online lessons. Oppia combines lesson authoring tools, exploration playback, learner feedback, and a web application built from Python and Angular/TypeScript components.

## Repository areas

- `core/` — application code, templates, services, and tests
- `extensions/` — custom interaction and rich-text extensions
- `assets/` — static assets and supporting scripts
- `data/` — application data and configuration
- `scripts/` — development, testing, and maintenance utilities
- `docker-compose.yml` — local container orchestration

## Development

Oppia has a substantial toolchain and pinned Python and JavaScript dependencies. Before changing code, follow the current setup guide and contributor instructions in the upstream project documentation rather than relying on a shortened install command here.

Useful repository entry points include:

- `README.md` files in `core/`, `extensions/`, `scripts/`, and `core/tests/`
- `Makefile` for supported developer commands
- `requirements.in` and `package.json` for dependency sources
- `LICENSE` and `NOTICE` for project terms

## Contribution principles

Keep changes focused, add or update tests, preserve accessibility and localization behavior, and run the narrowest applicable checks before broader suites. Do not commit credentials, generated dependency changes, or personal development data.

This copy follows the upstream Oppia project and should retain its licensing and attribution notices.
