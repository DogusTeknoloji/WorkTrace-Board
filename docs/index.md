---
layout: home
title: WorkTrace Board
---

> **WorkTrace Board** records user interactions on the current tab and turns them into **human-readable test steps** with suggested **XPath/CSS selectors**. All processing is **on-device**.

[➜ Install from Chrome Web Store](#) ·
[Privacy](/worktrace-board/privacy) ·
[Support](/worktrace-board/support) ·
[Changelog](/worktrace-board/changelog)

## Highlights

- Creates clear **action sentences** from clicks, inputs, menu selections
- Robust **XPath/CSS** suggestions with de-duplication
- **Copy** scenario or single path with one click
- **Local save/load** using `chrome.storage` (no servers)
- Works well with **iframes**, popups, and dynamic grids

## How it works

1. Click the extension icon (user-initiated).
2. A lightweight content script listens to interactions on the active tab.
3. The panel builds a step list you can **copy** or **save**.

## Permissions (why)

- `activeTab` – run only on the page you activate
- `scripting` – inject content script & observe DOM events
- `storage` – store preferences & scenarios locally
- `clipboardWrite` – enable “Copy Path / Copy Scenario”
- _(optional)_ `tabs` – show status/open options
- _(restricted if used)_ `host_permissions` – limit to specific domains

## Privacy, in short

- On-device processing
- No remote servers
- No PII/credentials/financial/health data  
  See the full [Privacy Policy](/worktrace-board/privacy).

## Screenshots

![WorkTrace Board](/worktrace-board/assets/hero.png)
