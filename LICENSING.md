# Licensing Strategy

This document describes the licensing approach across EndstoneMC repositories.

## Overview

| Category | License | Repositories |
|----------|---------|-------------|
| Core framework | Apache-2.0 | endstone |
| Ecosystem plugins | Apache-2.0 | endweave, sentry-crashpad |
| Templates and tools | MIT | python-example-plugin, cpp-example-plugin, stubgen, dwarf2cpp, bedrock-dumper, bedrock-server-data, remote-dev, pterodactyl |
| Infrastructure (dual-licensed) | AGPL-3.0 or commercial | endgate |

## Rationale

**Apache-2.0** for the core framework and ecosystem plugins provides patent protection and
clear contribution terms while remaining permissive. Plugin developers can use any license
for their own plugins.

**MIT** for templates, tools, and examples keeps them as simple and permissive as possible.
Developers forking a template should not be burdened by license complexity.

**AGPL-3.0** for infrastructure services is dual-licensed. The open source AGPL-3.0 license
requires any SaaS or hosted service running a modified version to release their changes.
Organizations that want to run modified versions without this obligation can acquire a
commercial license. Contact hello@endstone.dev for commercial licensing inquiries.

## For Contributors

By contributing to any EndstoneMC repository, you agree to license your contribution under
that repository's existing license. See [CONTRIBUTING.md](CONTRIBUTING.md) for details.
