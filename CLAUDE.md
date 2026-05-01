# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Part of `personal-os`

This repo is a satellite of [`personal-os`](file:///Users/jmattiello/Workspace/personal-os) at `~/Workspace/personal-os`. A fresh agent session here should read `personal-os/AGENTS.md` first for shared conventions:

- **`VOICE.md`** — voice rules. The profile README is public-facing; voice still applies.
- **`decisions/`** — cross-repo MADR-numbered ADRs.
- **`journal/`** — daily orchestration log; touch entries when shipping work in this repo.
- **`INBOX.md`** — things-to-act-on across all projects.
- **`wiki/projects-index.md`** — registry of every active repo and how it relates to this one.

Don't edit `personal-os/raw/` from a satellite — that's the central drop-zone, one-way.

## Project Overview

`github.com/JoeMatt` profile README repo. The single `README.md` here drives the landing page Joe's profile shows visitors. Pinned repos and bio are managed via the GitHub UI, not this file — `INBOX.md` in `personal-os` tracks the manual GitHub UI items Joe owes himself.

## Repo-specific notes

- **Voice register**: this is a personal profile, so a slightly warmer register than release notes is fine — but the bans in `personal-os/VOICE.md` (no `Crucially`, `It's worth noting`, marketing verbs, triplet adjectives) still apply.
- **Specifics over slogans**: every claim about Joe's projects should anchor to a number, link, or proper noun. "Provenance EMU creator (388k+ App Store DLs). 3 US patents." beats "experienced engineer."
- **Don't add features the profile doesn't have**: the README is plain Markdown rendered by GitHub. No GitHub Actions live in this repo (it isn't `.github`).

## Editing checklist

- Pinned-repo list, bio, Twitter handle, location are GitHub-account settings, not file edits. Leave those to Joe.
- The `images/` and `assets/` paths in the README resolve relative to this repo on `raw.githubusercontent.com`; if you add an image, commit it here.
- The shields.io badges hardcode the username `joematt` (lowercase). Don't rewrite to `JoeMatt` casing — shields.io rewrites it anyway and you'll just churn the diff.
