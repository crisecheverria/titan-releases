# Titan

An AI-native terminal for macOS: shells on a real terminal (libghostty) and Claude Code
sessions as a readable feed, side by side in tabs and splits, with a browser agents can
drive and actions you can script. Agents such as pi and Codex work too, kept to their own panes.

**[What it does, with demos →](https://cristianecheverria.com/titan/)**

## Download

**[Latest release](https://github.com/crisecheverria/titan-releases/releases/latest)**: open
`Titan-<version>.dmg` and drag Titan to Applications. Builds are signed with a Developer ID
and notarized by Apple.

Needs macOS 26 (Tahoe) on an Apple Silicon Mac. Claude panes need
[Claude Code](https://claude.com/claude-code) installed and signed in; shells work without it.

## Updates

Titan checks this repository once a day and shows a newer version in the tab bar, with
its notes and **Install and Restart**. Your shells and Claude sessions stay open through
the restart. **Titan → Check for Updates…** looks at once; `check-updates = false` in
`~/.config/titan/config` turns the daily check off.

## Feedback

Titan is a personal project and I'd like to hear what you think: what works, what doesn't,
what you'd want next. [Open an issue](https://github.com/crisecheverria/titan-releases/issues/new).

This repository holds releases only; the source is private.
