# SiriusAgent

SiriusAgent is the public home for Sirius: a native macOS agent runtime created
by Mikholae Hutchinson.

This repository is for the public product presence, release notes, packaged app
distribution, and agent-made demonstrations. It is not the Sirius source-code
repository.

## What Sirius Is

Sirius is a standalone macOS app for running practical AI agents against real
workspaces. It combines a native desktop shell with agent runtime services for
research, coding, local files, browser work, terminal workflows, Git history,
and release-ready artifacts.

The product goal is simple: agents should be able to do serious work in a real
Mac environment, and the result should be inspectable enough to publish.

## Public Demos

This account will host demos and public artifacts produced with SiriusAgent.
Demos may include agent-authored READMEs, receipts, static sites, screenshots,
videos, and GitHub Pages previews.

The first public demos are expected to show what an agent can build or review
from an ordinary local project, while keeping private source code out of this
public repository.

## Releases

SiriusAgent will be distributed as a signed standalone macOS app. Public release
artifacts, when available, will be attached through GitHub Releases or linked
from this repository.

Current builds are **strict pre-release unstable builds**. They are published
only so early testers can validate installation and auto-update behavior. Do
not treat any alpha build as an RC, production release, compatibility promise,
or support boundary.

Source code is not published here.

## Recommended System Requirements

Minimum recommended Mac: Apple Silicon M2 or newer with 16 GB RAM.

Sirius also requires a user-installed Python to be available for local tools,
MCP servers, skills, document workflows, and other integrations that launch
Python outside the app bundle. The app bundles its own runtime for Sirius
itself, but user-owned tool processes should be able to run `python3` from a
normal Terminal login shell.

Recommended Python installs:

- Homebrew Python on Apple Silicon: `/opt/homebrew/bin/python3`
- Python.org macOS installer: `/Library/Frameworks/Python.framework/Versions/3.x/bin/python3`
- Version-manager shims when configured in your login shell: `~/.pyenv/shims/python3`, `~/.asdf/shims/python3`, or `~/.local/bin/python3`
- Xcode Command Line Tools Python, when present: `/usr/bin/python3`

For best results, open a new Terminal window and confirm `python3 --version`
works before using Python-backed tools in Sirius.

## Authorship

SiriusAgent is built and directed by Mikholae Hutchinson. Demonstration content
may be produced by agents running inside Sirius, and those demos can identify
themselves as agent-made work.

## Repository Boundary

This repository should stay lightweight:

- product README and public docs
- GitHub Pages content
- release notes and download links
- screenshots, videos, and demo receipts
- agent-facing instructions for maintaining the public repo

It should not contain the Sirius app source tree, private workspace files,
runtime logs, credentials, local configuration, or unpublished implementation
details.
