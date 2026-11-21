# aPaper 0.1.3

[English](en.md) · [简体中文](zh-Hans.md) · [繁體中文](zh-Hant.md) · [日本語](ja.md) · [한국어](ko.md)

aPaper 0.1.3 makes updates safer and setup more reliable, while improving Dogzee account recovery and the Quick Research shortcut.

## Updates and setup

- The update dialog now shows the size of the package that will actually be downloaded, including a selected delta package.
- Known-incompatible delta updates are skipped before downloading, while the full package remains available as a fallback. The update metadata reader no longer crashes when an appcast contains structured delta metadata.
- Setup requests Documents access only after you click Authorize. If access is already granted, setup skips that step. Your language choice is kept outside workspace data, so replacing the workspace does not restart language setup.
- The Quick Research menu-bar shortcut control now fits its label instead of leaving excess space.

## Dogzee account recovery

- A linked Dogzee management token can be recovered from the signed-in account binding when local credentials are missing, preventing repeated logins from exhausting the account token limit.
- Fixed the optional account-service binding path used during Dogzee token recovery.

## Download and installation

On an Apple silicon Mac with macOS 14.6 or later, [download the DMG](https://github.com/YociLam/aPaper/releases/download/v0.1.3-b1009/aPaper.dmg), open it, and drag aPaper into Applications. To update manually, quit aPaper and replace the existing copy in Applications. See the [installation guide](https://github.com/YociLam/aPaper/blob/main/INSTALL.md) for details.

## Full changelog

See the [full changelog](https://github.com/YociLam/aPaper/blob/main/CHANGELOG.md) for the complete list of changes.
