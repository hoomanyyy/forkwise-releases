<div align="center">

<a href="https://forkwiseai.com"><img src="https://forkwiseai.com/logo.svg" width="80" height="80" alt="Forkwise"></a>

# Download Forkwise

**The open-source AI engineer that plans, builds, runs and checks real projects.**
Version 4.0.0 · November 23, 2026

[![Windows](https://img.shields.io/badge/Windows-download-0078d4?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/hoomanyyy/forkwise-releases/releases/download/current/forkwise-desktop-windows.exe)
[![macOS](https://img.shields.io/badge/macOS-download-1a1915?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/hoomanyyy/forkwise-releases/releases/download/current/forkwise-desktop-macos-arm64.dmg)
[![Linux](https://img.shields.io/badge/Linux-download-f59e0b?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/hoomanyyy/forkwise-releases/releases/download/current/forkwise-desktop-linux.AppImage)
[![Android](https://img.shields.io/badge/Android-download-2bb673?style=for-the-badge&logo=android&logoColor=white)](https://github.com/hoomanyyy/forkwise-releases/releases/download/current/forkwise-android.apk)

[Website](https://forkwiseai.com) · [Open-source core](https://github.com/hoomanyyy/Forkwise-AI) · [Docs](https://forkwiseai.com/docs) · [All files](https://github.com/hoomanyyy/forkwise-releases/releases/tag/current)

<img src="https://forkwiseai.com/site/desktop-chat.webp?v=4" alt="Forkwise Desktop: explorer, editor, terminal and the agent" width="100%">

</div>

## Forkwise Desktop

A Cursor-style editor built around an agent that finishes the job.

- **This computer or Cloud.** Work in your own folders and terminal, or switch the same window to a cloud workspace from the title bar.
- **A real editor.** File explorer, Monaco tabs, search in files, Ctrl P and a command palette.
- **Real terminals.** PowerShell, cmd, Git Bash, WSL, bash or zsh, several at once.
- **The agent beside your code.** Every read, edit and command shows up as it happens. Choose Agent, Plan or Ask first.
- **Any model.** Ours, or your own OpenAI, Anthropic, Gemini, OpenRouter or OpenAI-compatible key.
- **You stay in control.** It only works in the folder you open. Ctrl+Alt+Shift+X stops everything at once.

## Which file do I need?

| System | File | Notes |
| --- | --- | --- |
| Windows 10 or 11 (64-bit) | [`forkwise-desktop-windows.exe`](https://github.com/hoomanyyy/forkwise-releases/releases/download/current/forkwise-desktop-windows.exe) | Guided installer. |
| macOS 12+ on Apple silicon | [`forkwise-desktop-macos-arm64.dmg`](https://github.com/hoomanyyy/forkwise-releases/releases/download/current/forkwise-desktop-macos-arm64.dmg) | Open the file and drag Forkwise to Applications. |
| Linux, most distributions | [`forkwise-desktop-linux.AppImage`](https://github.com/hoomanyyy/forkwise-releases/releases/download/current/forkwise-desktop-linux.AppImage) | `chmod +x` the file, then run it. |
| Debian and Ubuntu | [`forkwise-desktop-linux.deb`](https://github.com/hoomanyyy/forkwise-releases/releases/download/current/forkwise-desktop-linux.deb) | `sudo apt install ./forkwise-desktop-linux.deb` |
| Android | [`forkwise-android.apk`](https://github.com/hoomanyyy/forkwise-releases/releases/download/current/forkwise-android.apk) | Allow installs from your browser when asked. |

These links always point to the newest version.

## First run

The installers are not code signed yet, so your system may ask before the first start:

- **Windows:** on "Windows protected your PC", choose **More info**, then **Run anyway**.
- **macOS:** if it says the app cannot be opened, right-click Forkwise in Applications and choose **Open**, or allow it in **System Settings, Privacy & Security**.
- **Linux:** make the AppImage executable first.

Then sign in. The app links this computer to your account by itself; you never paste a token.

## Open source

The Forkwise core, the agent and the web app these apps run on, is open source at **[github.com/hoomanyyy/Forkwise-AI](https://github.com/hoomanyyy/Forkwise-AI)**. If Forkwise helps you, a star there means a lot.

---

<details>
<summary><b>For maintainers: how this page is published</b></summary>

This repository only holds the downloads. Everything here is written by the **Desktop app release** workflow in the private Forkwise repository:

1. Bump `version` in `desktop-app/package.json` and merge to `main` (or push a `desktop-vX.Y.Z` tag).
2. The workflow builds Windows, macOS and Linux, creates the release in `forkwise`, replaces the files of the release **current** here, and rewrites this README from `releases/README.md`.

It needs the repository secret **`RELEASES_TOKEN`** in that repository: a fine-grained token with **Contents: Read and write** on `forkwise-releases` only. The Android APK is added by the **Android app** workflow, or by running **Publish downloads** by hand.

</details>
