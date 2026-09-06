# Echo Studio for Windows

Release downloads for [Echo Studio](https://echomana.com/studio/), the desktop app that turns a manuscript into a chaptered audiobook with on-device neural narration.

**Status: alpha.** Studio is very much still being built. It renders real books today, and it will also crash, stall, or mispronounce things. Please tell us when it does.

## Reporting a problem

- **In the app:** press **Report a problem** in the footer, or **Send a report about this** under any error. It sends the app's diagnostic log with one click and gives you a reference like `ECHO-3F9A2C1B`. The dialog shows exactly what will be sent; it never includes your book text, its title, or file names.
- **If the app never opened** (the installer would not run, Windows blocked it): use the form at [echomana.com/studio/#report](https://echomana.com/studio/#report).
- **If you have a GitHub account,** [issues](../../issues) work too. Please do not paste your book text into a public issue.
- The log lives at `%APPDATA%\Echo Studio\logs\studio.log` if anyone asks you for it.

## Install

Download the latest `EchoStudio-Setup-<version>.exe` from [Releases](../../releases), run it, and it installs for your user account (no admin rights).

The alpha builds are not code-signed yet, so Windows shows "Windows protected your PC" on first run. Click **More info**, then **Run anyway**. Every release lists its SHA-256 so you can check the file matches what we published:

```powershell
Get-FileHash .\EchoStudio-Setup-<version>.exe
```

## Requirements

- Windows 10 (version 1809) or Windows 11, 64-bit
- 8 GB RAM recommended
- About 1 GB of disk for the app and a working folder for renders
- No graphics card needed

This repository holds only release files and a small scheduled health check. The source lives in a private repository.
