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

**Free for personal use.** Hearth is free for your own projects, studies and
hobbies. Use by a company or organisation, or as part of paid work, needs a
business licence: open an issue titled "Business licence" and the author will
reply.

**Ideas and problems are welcome.** Open an issue to suggest an improvement or
report a problem. Hearth's source is private, so changes are made by its author.

Use is governed by the licence agreement shown by the installer (`EULA.txt`).
