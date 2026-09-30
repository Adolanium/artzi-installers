# Artzi installers

Installers for [Artzi](https://artzi.app), the personal AI assistant that runs on your computer.

## 0.1.0

| Platform | File |
|---|---|
| macOS, Apple Silicon (M1 and later) | [Artzi-0.1.0-mac-apple-silicon.dmg](v0.1.0/Artzi-0.1.0-mac-apple-silicon.dmg) |
| macOS, Intel | [Artzi-0.1.0-mac-intel.dmg](v0.1.0/Artzi-0.1.0-mac-intel.dmg) |
| Windows 10 and 11, 64-bit | [Artzi-0.1.0-windows-x64-setup.exe](v0.1.0/Artzi-0.1.0-windows-x64-setup.exe) |

Checksums are in [v0.1.0/SHA256SUMS.txt](v0.1.0/SHA256SUMS.txt).

## These builds are not signed yet

Your computer will warn you the first time you open Artzi.

**macOS:** open the `.dmg` and drag Artzi to Applications. Open it once; macOS will refuse. Then go to **System Settings → Privacy & Security**, scroll down to the message about Artzi and click **Open Anyway**. If macOS says the app is damaged, run this in Terminal, then open it again:

```sh
xattr -dr com.apple.quarantine /Applications/Artzi.app
```

**Windows:** run the installer. If SmartScreen says "Windows protected your PC", click **More info**, then **Run anyway**.
