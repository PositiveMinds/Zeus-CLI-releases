# Zeus — binaries & installers

This is the **public release mirror** for [Zeus](https://github.com/PositiveMinds/Zeus-CLI)
(the database-free AI coding agent). Prebuilt binaries for each release are
published here by CI, so you can install Zeus **without installing Rust**.

The source repository is private; this repo contains only binaries and
installer scripts.

## Install (Windows)

**PowerShell:**
```powershell
irm https://raw.githubusercontent.com/PositiveMinds/Zeus-CLI-releases/main/install.ps1 | iex
```

**cmd:**
```batch
curl -L https://raw.githubusercontent.com/PositiveMinds/Zeus-CLI-releases/main/install.bat | cmd
```

Either installer downloads the latest prebuilt binary to `%LOCALAPPDATA%\zeus`
and adds it to your user PATH. Verify with `zeus doctor`.

## Releases

See [Releases](https://github.com/PositiveMinds/Zeus-CLI-releases/releases) for
binaries:
- `zeus-x86_64-pc-windows-msvc.zip` (Windows)
- `zeus-x86_64-unknown-linux-gnu.tar.gz` (Linux)
- `zeus-x86_64-apple-darwin.tar.gz` / `zeus-aarch64-apple-darwin.tar.gz` (macOS)