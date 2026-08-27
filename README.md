
<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/tldraw/tldraw-offline/raw/main/assets/logo-dark.svg" />
  <img height="52" alt="tldraw offline" src="https://github.com/tldraw/tldraw-offline/raw/main/assets/logo-light.svg" />
</picture>
  <br><br>
<img height="600" alt="tldraw offline app" src="https://github.com/user-attachments/assets/0c33c884-3b43-45b5-9e0e-77673b1306f0" />
</div>

# tldraw offline

A local whiteboard for you and your agents.

tldraw offline is a desktop application for drawing, diagramming, whiteboarding, and more on [tldraw's infinite canvas](https://tldraw.com). There are no accounts or servers, and the app works without an internet connection. Your documents are saved as portable `.tldraw` files that you can keep private, back up, or share.

## Download

Download tldraw offline for macOS, Windows, or Linux at [offline.tldraw.com](https://offline.tldraw.com), or browse the [latest GitHub release](https://github.com/tldraw/tldraw-offline/releases/latest).

| Platform | Available builds |
| --- | --- |
| macOS | Universal DMG for Apple silicon and Intel |
| Windows | Installer for x64 or Arm64 |
| Linux | AppImage for x64 or Arm64; Debian package for x64 |

On macOS, you can also install tldraw offline with [Homebrew](https://brew.sh):

```sh
brew install --cask tldraw
```

The app checks for updates when it starts. You can also check manually from the application menu.

## Get started

1. Open tldraw offline and select **New file**.
2. Draw, add text and media, or build a diagram on the canvas.
3. Choose **File → Save** and select a name and location.
4. Reopen the document from the Home screen, the application menu, or your file browser.

Each document opens in its own window. tldraw offline automatically keeps working copies of open documents and can restore unsaved work after an unexpected exit, but recovery is not a replacement for saving and backing up your files.

For installation instructions, file management, keyboard shortcuts, troubleshooting, and agent setup, read the [tldraw offline user manual](https://tldraw.notion.site/User-manual-tldraw-offline-39a3e4c324c080e7b2eacc5afd078e85?pvs=74).

## Local files

`.tldraw` is the native and preferred file format. A file contains the canvas, its pages and stored media, and any embedded document script. Files work across macOS, Windows, and Linux.

Legacy `.tldr` files can also be opened and exported. Opening one imports it as a new, unsaved document and leaves the original file unchanged.

> [!IMPORTANT]
> tldraw offline does not currently merge changes made to an open file by another program, sync client, Git operation, or computer. Close the document before replacing it externally, then reopen it.

## Bring your own AI

tldraw offline can work with coding agents such as [Codex](https://openai.com/codex/), [Claude Code](https://claude.com/product/claude-code), [Pi](https://github.com/badlogic/pi-mono), and [OpenCode](https://opencode.ai). An agent can inspect an open canvas, make changes, and create reusable document scripts that add new behavior to a file.

This is powerful by design. An agent with access to the app can read and edit your documents, and scripts stored in a `.tldraw` file can run when the file is opened. Only grant access to agents you trust and only open files from sources you trust. See the [user manual](https://tldraw.notion.site/User-manual-tldraw-offline-39a3e4c324c080e7b2eacc5afd078e85?pvs=74) for setup and security details.

## Learn more

- Read the [user manual](https://tldraw.notion.site/User-manual-tldraw-offline-39a3e4c324c080e7b2eacc5afd078e85?pvs=74)
- Join the [tldraw Discord](https://discord.tldraw.com)
- Follow [tldraw on X](https://x.com/tldraw)
- Build your own canvas application with the [tldraw SDK](https://tldraw.dev)

## License

tldraw offline is not open source. All rights reserved.
