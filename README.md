# Echo Studio for Windows

Release downloads for [Echo Studio](https://echomana.com/studio/), the desktop app that turns a manuscript into a chaptered audiobook with on-device neural narration.

**Status: alpha.** Studio is very much still being built. Expect rough edges, and please tell us about them: the app has a **Report a problem** button that sends diagnostics with one click, and there is a report form at [echomana.com/studio](https://echomana.com/studio/#report). If you have a GitHub account, [issues](../../issues) work too.

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

This repository holds only release files. The source lives in a private repository.
