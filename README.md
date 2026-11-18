# Moneydoot ITR — desktop downloads

Public installers for the Moneydoot ITR desktop app.

The source repository is private. These release assets are published
automatically by the release workflow.

## Download

- [macOS universal (Apple Silicon + Intel)](https://github.com/vijaysetia/moneydoot-itr-releases/releases/latest/download/Moneydoot-ITR-mac-universal.dmg)
- [Windows x64 installer](https://github.com/vijaysetia/moneydoot-itr-releases/releases/latest/download/Moneydoot-ITR-windows-x64-setup.exe)
- [SHA-256 checksums](https://github.com/vijaysetia/moneydoot-itr-releases/releases/latest/download/SHA256SUMS.txt)
- [Version](https://github.com/vijaysetia/moneydoot-itr-releases/releases/latest/download/version.txt)

The download page on [moneydoot.in](https://www.moneydoot.in/products/income-tax-app/download)
is available to Moneydoot Pro users. These direct GitHub links are public.

## Installation note

Builds are currently unsigned.

- **macOS:** after opening the DMG, right-click the app and choose **Open**,
  or allow it in **System Settings → Privacy & Security**.
- **Windows:** if SmartScreen appears, choose **More info → Run anyway**.

## Verification

```bash
shasum -a 256 -c SHA256SUMS.txt
```

Tax data stays on your computer. The desktop app uses the moneydoot account
login only for authentication and access control.
