# Hearth releases

Built installers for **Hearth**, the Windows desktop app that keeps Claude
session windows open and shows remaining allowance across Claude, Codex, Grok,
Kimi and Antigravity. This repository holds only release files; the source is
private.

**Install on Windows** (no administrator rights, no Python):

```powershell
iex (iwr https://github.com/George-Orf/hearth-releases/releases/latest/download/install.ps1 -UseBasicParsing).Content
```

or download `Hearth-Setup-<version>.exe` from the latest release and run it.
Every file is listed with its SHA-256 in `SHA256SUMS.txt`. Hearth updates
itself from here once installed.

Use is governed by the licence agreement shown by the installer (`EULA.txt`).
