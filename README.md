# tldraw offline

A desktop application for tldraw’s infinite canvas. Built with [tldraw](https://tldraw.dev) and Electron.

It is:
Local. Everything lives on your machine, no internet needed.
File-based. Save, back-up, and share any file you’re working on.
Dangerous. Your agent can read, edit, and script on your canvas.

## Download

Get the latest release from [offline.tldraw.com](https://offline.tldraw.com/) or [Releases page](https://github.com/tldraw/tldraw-desktop/releases/latest).

| Platform | Download |
| --- | --- |
| macOS (Apple Silicon + Intel) | `tldraw-{version}-universal.dmg` |
| Windows x64 | `tldraw-{version}-win-x64.exe` |
| Windows ARM64 | `tldraw-{version}-win-arm64.exe` |
| Linux x64 | `tldraw-{version}-linux-x64.AppImage` or `.deb` |
| Linux ARM64 | `tldraw-{version}-linux-arm64.AppImage` |

## Usage

tldraw offline is a desktop application that you can use to make diagrams, whiteboards, notes, and more. The files you create are saved as .tldraw files. You can draw pictures, add images, embed websites, and more.

If you already know about [tldraw.com](https://www.tldraw.com), then tldraw offline is very similar, except that it is an offline, file-based, single-player experience. If you want a free hosted product, use [tldraw.com](https://www.tldraw.com).

## Danger

The application is designed to work with AI agents such as OpenAI’s Codex, Anthropic’s Claude, and coding harnesses such as Pi, OpenCode, and any other. These AI agents can write scripts that will run when a file is opened as well as query, screenshot, or script inject the running application through a local server.

Use the dangerous power of tldraw offline to **create unusual experiences.**

## More

Read the release notes on [GitHub](https://github.com/tldraw/tldraw-desktop/releases). Join the [Discord](https://discord.tldraw.com/). Follow [tldraw on Twitter/X](https://x.com/tldraw).

Build your own **canvas application** with the [tldraw SDK](https://tldraw.dev/).

## Auto-updates

The app checks for updates on launch. When a new version is available, you'll be prompted to download and install it.

## Development

Source code lives in the [`tldraw-internal`](https://github.com/tldraw/tldraw-internal) monorepo at `apps/public/desktop/`.

## License

This project is not open source. All rights reserved.
