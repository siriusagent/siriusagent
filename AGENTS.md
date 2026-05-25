# AGENTS.md

Instructions for AI agents working in this public repository.

## Purpose

This is the public presence and distribution repository for SiriusAgent. It is
not the Sirius source-code repository.

Agents may update public-facing documentation, GitHub Pages content, release
notes, screenshots, videos, and demo receipts. Keep the repository suitable for
public visitors and app distribution.

## Hard Boundaries

- Do not add Sirius source code.
- Do not add private project files, local workspace snapshots, terminal logs, or
  internal debugging transcripts.
- Do not add credentials, tokens, Keychain exports, environment files, signing
  material, provisioning files, or private configuration.
- Do not imply that this repository is the complete app source unless Mikholae
  explicitly changes the release strategy.
- Do not route public release work through a different GitHub owner unless the
  user explicitly asks.

## Allowed Content

- `README.md` and product documentation.
- GitHub Pages files for public demos.
- Public demo receipts that clearly describe what an agent produced.
- Release notes and links to signed standalone app downloads.
- Screenshots, videos, and static assets intended for public display.
- Small metadata files needed by GitHub Pages or Releases.

## Voice

Use clear product language. Credit Mikholae Hutchinson as the creator of
SiriusAgent. Demo artifacts may state that they were made by agents running in
Sirius when that is true.

Avoid hype, fake open-source claims, and private implementation details. Public
copy should be accurate, direct, and easy for a developer or evaluator to scan.

## Before Pushing

Confirm the diff contains only public documentation, static demo assets, release
metadata, or other explicitly approved public artifacts.

If source code or private files appear in the diff, stop and remove them before
committing.
