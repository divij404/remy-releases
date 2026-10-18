# Remy

**Turn messy screen recordings into polished demos.**

Remy records your screen, tidies the footage with smooth zooms and pans, and exports a finished video, with no timeline wrestling.

**[Download the latest beta →](https://github.com/divij404/remy-releases/releases/latest)**

> Remy is in beta for Windows. Source isn't public yet. The installer is unsigned, so Windows SmartScreen may warn: choose **More info → Run anyway**.

## What it does

- **Record and polish.** Capture your screen and voice, then trim, cut, speed up, redact private parts, and add zooms that follow your clicks.
- **Projects and scripts.** Join takes into one demo, write a line of narration per clip, read it from a teleprompter, and Remy retimes the video to your voice. Captions come from your script.
- **Let an AI agent help.** Connect Claude, Codex or Cursor through Remy's built-in MCP server. An agent can review your takes, plan a demo with you, write the script and suggest edits. Every change waits for your approval in the app, can be undone, and an agent never records for you or deletes a recording.
- **Plan a demo with an agent** *(new in 0.4 beta)*. The agent proposes a story, checks it against your footage, and asks you for the clips that are missing, each with exact steps. Recording only starts when you press Start.

## Install

1. Download the `.exe` from the [latest release](https://github.com/divij404/remy-releases/releases/latest).
2. Run it. Remy updates itself from then on (**Settings → Check for updates**).

## Connect an AI agent

In Remy, open **Settings → AI agents** and copy the one-line command for your tool. For Claude Code it looks like:

    claude mcp add remy -- "<path shown in Remy>\remy-mcp.exe" --mcp

## Feedback

Found a bug or have an idea? [Open an issue](https://github.com/divij404/remy-releases/issues).
