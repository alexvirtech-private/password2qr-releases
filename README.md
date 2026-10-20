# Password2QR — desktop app downloads

This repository hosts the public installer downloads for the
[Password2QR](https://password2qr.com) desktop app. The application source
lives in the Password2QR monorepo; this repository contains releases only.

## Download

- **Windows (x64):** [Password2QR-Setup.exe — latest version](https://github.com/alexvirtech-private/password2qr-releases/releases/latest/download/Password2QR-Setup.exe)
- All versions and their SHA-256 checksums: [Releases](https://github.com/alexvirtech-private/password2qr-releases/releases)

## Verify before installing

Each release lists the installer's SHA-256 checksum. After downloading,
compare it (PowerShell):

```powershell
Get-FileHash .\Password2QR-Setup.exe -Algorithm SHA256
```

The installers are currently **unsigned**: Windows SmartScreen will warn on
first run ("Windows protected your PC" → More info → Run anyway). Verifying
the checksum above is the integrity check until code signing lands.

## What the app does

Create strong passwords from a memorable phrase, keep them as files or QR
codes, and restore them locally — offline by design. Passwords are processed
on your device only. See https://password2qr.com for details and the
whitepaper.
