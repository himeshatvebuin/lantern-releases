# Lantern releases

Installers for Lantern, a desktop app that scans Git repositories for vulnerable dependencies, leaked secrets and risky configuration. This repo holds only the releases.

Download the [latest release](https://github.com/himeshatvebuin/lantern-releases/releases/latest):

| Platform | File |
|---|---|
| Windows 10 and 11 (64-bit) | `Lantern-Setup-<version>.exe` |
| macOS on Apple Silicon (M1 or newer) | `Lantern-<version>-arm64.dmg` |

Check the file against `SHA256SUMS.txt` from the same release before installing. Lantern opens only with a personal access key from your Lantern admin, and it needs Git 2.39.1 or newer.

Lantern 0.2.0 and later look for new releases here by themselves: Windows installs them on restart, and on a Mac the `.dmg` is downloaded for you.
