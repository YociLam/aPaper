# aPaper 0.1.4

[English](https://github.com/YociLam/aPaper/blob/main/releases/0.1.4/en.md) · [简体中文](https://github.com/YociLam/aPaper/blob/main/releases/0.1.4/zh-Hans.md) · [繁體中文](https://github.com/YociLam/aPaper/blob/main/releases/0.1.4/zh-Hant.md) · [日本語](https://github.com/YociLam/aPaper/blob/main/releases/0.1.4/ja.md) · [한국어](https://github.com/YociLam/aPaper/blob/main/releases/0.1.4/ko.md)

This release makes announcements easier to catch, keeps the reader usable in narrow windows, and improves recovery when reopening the workspace.

## New Features

- **Rich announcements.** Messages can be tailored to your language and client. The panel supports formatted text, images, links and buttons. Video links open in your browser.
- **Read when convenient.** A new message briefly appears in the island. Click it or the bell in the lower-right corner to read it. If an update button is visible, the bell sits above it. Cached unread messages reopen at the next launch, even offline. Opening one leaves newer messages available.
- **Community invitation.** In Simplified or Traditional Chinese, About includes the aPaper QQ group invitation and QR code.

## Improvements

- **Adaptive reading layout.** As the window narrows, the library sidebar closes first, the reader switches from two panes to one, then the right inspector closes. Widen the window to restore your previous choices in reverse order, with the same animations as the manual controls.
- **Dogzee defaults.** Paper Mentor, Research Assistant and Knowledge Steward now default to GPT 6.2 Sol with medium reasoning.

## Bug Fixes

- **Message composer.** Scroll a long draft under the pointer without moving the conversation. After sending, the composer keeps the height you set.
- **Workspace recovery.** Reopening the main window from the Dock or Quick Research restores the workspace and its announcement controls. A failure to install or validate an optional assistant profile no longer blocks entry.
- **Reasoning compatibility.** If a provider rejects a reasoning level, aPaper tries another supported level on the same model and remembers the first successful level for matching requests.

## Download and installation

Versions 0.1.1, 0.1.2 and 0.1.3 have direct delta updates to 0.1.4. The full update package is available when a delta cannot be used. For 0.1.0, use the DMG below.

On an Apple silicon Mac running macOS 14.6 or later, [download the DMG](https://github.com/YociLam/aPaper/releases/download/v0.1.4-b1010/aPaper.dmg), open it and drag aPaper into Applications. To update manually, quit aPaper and replace the installed copy. See the [installation guide](https://github.com/YociLam/aPaper/blob/main/INSTALL.md).

## Full changelog

See the [full changelog](https://github.com/YociLam/aPaper/blob/main/CHANGELOG.md) for the release history.
