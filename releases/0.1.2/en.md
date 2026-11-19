# aPaper 0.1.2

[English](en.md) · [简体中文](zh-Hans.md) · [繁體中文](zh-Hant.md) · [日本語](ja.md) · [한국어](ko.md)

aPaper 0.1.2 adds Quick Research to the macOS menu bar and improves how you work with PDFs, attachments, translations, and models.

## New Features

- **Quick Research.** Open it from the macOS menu bar. Set a shortcut in Settings, or clear it with Escape while recording or with the clear button.
- **PDF evidence in Paper Mentor.** Ask about an attached PDF, then open a citation at the quoted page with the passage highlighted.

## Improvements

- **In-app previews.** Open attachments and Knowledge sources without leaving the workspace. Zoom documents, or mark up and crop images before saving a separate copy.
- **Quoted follow-ups.** Continue a follow-up while the main reply is running, with each queued message retaining its own attachments.
- **Model setup.** New installations start empty. Updates retain configured providers and models, setting unsupported reasoning levels back to Automatic.

## Bug Fixes

- **Reader controls.** Parallel translation stays visible for every target language. When the PDF is already in that language, the reader shows a notice and leaves the button in its normal style. Deleting an annotation asks for confirmation.
- **Ergouzi and account forms.** Restore cached models at startup, remove Ergouzi providers after unlinking, and display a 30-second resend countdown after a successful code request. Switching account forms hides passwords again.
- **Provider setup and conversation reliability.** Fix first-time custom provider setup, make it easier to remove rejected attachments, and restore Research Assistant retries after a failed start.

## Download and installation

On an Apple silicon Mac with macOS 14.6 or later, [download the DMG](https://github.com/YociLam/aPaper/releases/download/v0.1.2-b1008/aPaper.dmg), open it, and drag aPaper into Applications. To update manually, quit aPaper and replace the existing copy in Applications. See the [installation guide](https://github.com/YociLam/aPaper/blob/main/INSTALL.md) for details.

## Full changelog

See the [full changelog](https://github.com/YociLam/aPaper/blob/main/CHANGELOG.md) for the complete list of changes.
