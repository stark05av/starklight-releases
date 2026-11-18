# StarkLight

A lighting console for churches, by Stark AV.

## Download

| | |
| --- | --- |
| **StarkLight for Mac** | [Download StarkLight 0.9.0 (build 108)](https://github.com/stark05av/starklight-releases/releases/latest/download/StarkLight.dmg) · macOS 14.0 or later |
| **StarkLight for Claude** | [Download the Claude connector](https://github.com/stark05av/starklight-releases/releases/latest/download/StarkLight-for-Claude.mcpb) · for Claude Desktop |

## Install StarkLight

1. Open **StarkLight.dmg** from your Downloads.
2. Drag **StarkLight** onto the **Applications** folder next to it.
3. Open StarkLight from Applications. The first time, it opens a demo show with its output off, so nothing changes on stage until you set up your lights.

**Updates come by themselves.** StarkLight checks for new versions, gets them ready in the background and asks before installing (or any time: **StarkLight › Check for Updates…**). It never downloads or installs in Sunday Mode, and the version you had is kept in case you need it back.

## Let Claude run the lights

You need StarkLight open on the same Mac, and [Claude Desktop](https://claude.ai/download).

1. Download **StarkLight-for-Claude.mcpb** above and double-click it. (Or in StarkLight: **Remote › Claude › Install in Claude Desktop**, the same thing with no download.)
2. Claude Desktop shows the StarkLight connector. Click **Install**.
3. In StarkLight, turn on **Remote › Claude › Let Claude control StarkLight**.

Then ask Claude things like "make the stage a slow blue-to-purple waterfall" or "build a cue list for Sunday". In Sunday Mode Claude can only look.

For Claude Code, run this in a terminal once StarkLight is in Applications:

```
claude mcp add --scope user starklight -- /Applications/StarkLight.app/Contents/MacOS/starklight-mcp
```

## What's new in 0.9.0 (build 108)

The Dock icon stays red while StarkLight is open.

[Every version](https://github.com/stark05av/starklight-releases/releases)
