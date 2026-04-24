# sgrapi

This repository contains skills and extensions that I use across projects. Note that I often fine-tune these for specific repos, so some items may need small adjustments before reuse.

It is released on npm as `sgrapi` for use with the [Pi](https://pi.dev/) package loader.

## Skills

All skills live in the [`skills`](skills) folder:

* [`/commit`](skills/commit) - Create git commits using concise Conventional Commits-style subjects.
* [`/frontend-design`](skills/frontend-design) - Design and implement distinctive frontend interfaces.
* [`/github`](skills/github) - Interact with GitHub using the `gh` CLI (issues, PRs, runs, APIs).
* [`/librarian`](skills/librarian) - Cache and refresh remote git repositories in `~/.cache/checkouts`.
* [`/mermaid`](skills/mermaid) - Create and validate Mermaid diagrams with Mermaid CLI tooling.
* [`/native-web-search`](skills/native-web-search) - Trigger native web search with concise summaries and source URLs.
* [`/pi-share`](skills/pi-share) - Load and parse session transcripts from shittycodingagent.ai/buildwithpi/pi.dev URLs.
* [`/summarize`](skills/summarize) - Convert files/URLs to Markdown via `uvx markitdown` and summarize.
* [`/tmux`](skills/tmux) - Drive tmux sessions via keystrokes and pane output scraping.
* [`/update-changelog`](skills/update-changelog) - Update changelogs with notable user-facing changes.
* [`/uv`](skills/uv) - Use `uv` for Python dependency management and script execution.
* [`/web-browser`](skills/web-browser) - Browser automation via Chrome/Chromium CDP.

## Pi Coding Agent Extensions

Custom extensions for Pi Coding Agent are in [`extensions`](extensions):

* [`answer.ts`](extensions/answer.ts) - Interactive TUI for answering questions one by one.
* [`btw.ts`](extensions/btw.ts) - Simple `/btw` side-chat popover with optional summary injection back into the main chat on close.
* [`control.ts`](extensions/control.ts) - Session control helpers (list controllable sessions, etc.).
* [`files.ts`](extensions/files.ts) - Unified file browser with git status + session references and reveal/open/edit/diff actions.
* [`split-fork.ts`](extensions/split-fork.ts) - `/split-fork` command to branch the current session into a new pi process in a right-hand Ghostty split.
* [`loop.ts`](extensions/loop.ts) - Prompt loop for rapid iterative coding with optional auto-continue.
* [`notify.ts`](extensions/notify.ts) - Native desktop notifications when the agent finishes.
* [`prompt-editor.ts`](extensions/prompt-editor.ts) - In-editor prompt mode selector with persistence, history, config, and shortcuts.
* [`session-breakdown.ts`](extensions/session-breakdown.ts) - TUI for 7/30/90-day session and cost analysis with usage graph.
* [`todos.ts`](extensions/todos.ts) - Todo manager extension with file-backed storage and TUI.
* [`uv.ts`](extensions/uv.ts) - Helpers for uv-based Python workflows.
* [`whimsical.ts`](extensions/whimsical.ts) - Replaces the default thinking message with random whimsical phrases.

## Pi Coding Agent Themes

Custom themes are in [`themes`](themes):

* [`dracula.json`](themes/dracula.json) - [Dracula](https://draculatheme.com/) theme.

## Intercepted Commands

Command wrappers live in [`intercepted-commands`](intercepted-commands):

* [`pip`](intercepted-commands/pip)
* [`pip3`](intercepted-commands/pip3)
* [`python`](intercepted-commands/python)
* [`python3`](intercepted-commands/python3)
