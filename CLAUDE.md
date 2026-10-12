# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) and GitHub Copilot CLI when working in this repository.

This folder is the `incrediblecrab/mlot-developer-media` repository: a public host for the animated demo GIFs embedded in the READMEs and pages of the npm packages, VS Code extensions and sites. It has no build step and no code.

## Rules

Other repositories embed these files through `https://raw.githubusercontent.com/incrediblecrab/mlot-developer-media/main/gifs/<name>.gif`, so every file name and path under `gifs/` is a public interface. Never move, rename or delete a GIF, and never change the default branch name, without first finding and updating every embed (search the sibling repositories for `mlot-developer-media`). Replacing a GIF's contents in place keeps every embed working. A new GIF goes in `gifs/` and in the README's table. Keep files reasonably small, since every README view downloads them.
