# Coinetic AI Security - Scoop bucket

Install [Coinetic AI Security](https://coinetic.io) with [Scoop](https://scoop.sh) - firewall and intrusion protection
for Windows Servers and PCs that bans password guessers and port scanners automatically.

```powershell
scoop bucket add coinetic https://github.com/Coinetic-AI-Security/scoop-bucket
scoop install coinetic/coinetic
```

- Run from an **administrator** PowerShell: Coinetic AI Security installs a Windows service.
- Starts the free 30-day trial (all features, no payment details). Installing accepts the
  [licence agreement](https://coinetic.io/eula).
- The installer is the signed `CoineticSetup.exe` from coinetic.io; the manifest pins its SHA-256 and is updated with
  every release. Coinetic also updates itself.
- Other ways to install: `winget install coinetic`, Chocolatey, or [coinetic.io](https://coinetic.io).

This repository holds only the install instructions for Scoop (download address and checksum) - no application code.

Coinetic AI Security - https://coinetic.io
