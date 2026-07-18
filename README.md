# Aurora Downloads

Compiled installers for **Aurora — the real-time AI meeting companion**.

This repository contains **release binaries only**. Aurora's source code is private
and is never published here.

## Download

Get Aurora from the official download page: **https://aurora-web-phi.vercel.app/download**

Or grab the latest installers directly from the
[Releases](https://github.com/musz2/aurora-downloads/releases/latest) page:

| Platform | File |
|---|---|
| macOS (Apple Silicon) | `Aurora-macOS-arm64.dmg` |
| macOS (Intel) | `Aurora-macOS-x64.dmg` |
| Windows 10/11 (x64) | `Aurora-Windows-x64-Setup.exe` |
| Linux (AppImage, x64) | `Aurora-Linux-x86_64.AppImage` |
| Linux (Debian/Ubuntu, x64) | `Aurora-Linux-amd64.deb` |

Every release includes a `SHA256SUMS.txt`. Verify a download with:

```sh
shasum -a 256 -c SHA256SUMS.txt --ignore-missing
```

## Early-access note

Current macOS builds are **unsigned and unnotarized** and are intended for
**internal testers only**. macOS Gatekeeper will warn that Aurora cannot be
verified and may block it entirely. If you are not a tester, use the
[Aurora web app](https://aurora-web-phi.vercel.app) — a signed, notarized
release is the next milestone. Only install Aurora from this repository or
the official website.

## Support

Web app: https://aurora-web-phi.vercel.app
