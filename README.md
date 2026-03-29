# Paperclip

<!-- VERSION:v2026.325.0 -->

[![GHCR](https://img.shields.io/badge/ghcr.io-janrk%2Fpaperclip-blue?logo=github)](https://github.com/JanRK/paperclip/pkgs/container/paperclip)
[![Version](https://img.shields.io/badge/version-v2026.325.0-blue)](https://github.com/JanRK/paperclip/pkgs/container/paperclip)
[![Upstream](https://img.shields.io/badge/upstream-paperclipai%2Fpaperclip-purple?logo=github)](https://github.com/paperclipai/paperclip)
[![License](https://img.shields.io/badge/license-MIT-green)](https://github.com/paperclipai/paperclip/blob/master/LICENSE)

Docker image for [paperclipai/paperclip](https://github.com/paperclipai/paperclip), published automatically to **GitHub Container Registry** on every upstream release.

## Quick start

```bash
docker pull ghcr.io/janrk/paperclip:latest
docker run -p 3100:3100 ghcr.io/janrk/paperclip:latest
```

Tags follow the upstream release format (e.g. `v2026.325.0`).

## What is Paperclip?

[Paperclip](https://github.com/paperclipai/paperclip) is open-source orchestration for zero-human companies. It coordinates teams of AI agents (OpenClaw, Claude Code, Codex, Cursor, etc.) into a company structure with org charts, budgets, governance, goal alignment, and agent coordination.

See the [upstream repo](https://github.com/paperclipai/paperclip) for full documentation, configuration, and development instructions.

## How it works

Automatically builds and publishes a new Docker image to GHCR on every [paperclipai/paperclip release](https://github.com/paperclipai/paperclip/releases).

## License

MIT — see [upstream LICENSE](https://github.com/paperclipai/paperclip/blob/master/LICENSE).
