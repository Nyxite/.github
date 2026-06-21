# Nyxite

**Your notes — self-hosted, encrypted, and entirely yours.**

*Notes, Yours — eXclusive, Inked, Tracked, Encrypted*

- [Website](https://nyxite.app)
- [Docs](https://nyxite.app/docs)
- [Discussions](https://github.com/orgs/Nyxite/discussions)

---

## What is Nyxite?

Nyxite is a self-hosted notes and documents platform you run on your own server.
It handles markdown, handwritten ink, and plain text side by side, syncs across all your devices, encrypts your data at rest, and keeps a full history of every change, without handing your notes to anyone else's cloud.

It's built for people who want the convenience of Notion or Obsidian-style tools, but with ownership and privacy as the starting point rather than an afterthought.

## Features

- **Three content types** — markdown, handwritten ink, and plain text, all first-class.
- **Cross-device sync** with per-file policies — keep a file server-synced, pinned local-only, or excluded entirely.
- **Encryption at rest** — envelope encryption with per-file AES-256-GCM keys wrapped by a master key held outside the database.
- **Live collaborative editing** — real-time co-editing, including anonymous guests via share links.
- **Flexible sharing** — share by link or by account.
- **Full version history** — every edit tracked and recoverable.
- **Secure auth** — Keycloak-based authentication with TOTP 2FA.

## Clients and stack

| Surface | Built with |
| --- | --- |
| Desktop (Windows / Linux) | C# + Avalonia UI |
| Android | Kotlin + Jetpack Compose |
| Web | Next.js + shadcn/ui |
| Server | C# / ASP.NET Core |

## Get started

- Browse the [repositories](https://github.com/orgs/Nyxite/repositories) to find the server and client apps
- Read the [self-hosting guide](https://nyxite.app/docs) to deploy on your own VPS
- Found a bug or have an idea? Open an issue or start a [discussion](https://github.com/orgs/Nyxite/discussions)

## Contributing

Contributions are welcome. Check the [contributing guide](https://github.com/Nyxite/.github/blob/main/CONTRIBUTING.md) and look for [good first issues](https://github.com/search?q=org%3ANyxite+label%3A%22good+first+issue%22+state%3Aopen&type=issues) to get started.
