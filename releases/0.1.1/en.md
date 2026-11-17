English · [简体中文](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/zh-Hans.md) · [繁體中文](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/zh-Hant.md) · [日本語](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/ja.md) · [한국어](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/ko.md)

aPaper 0.1.1 improves Knowledge task recovery, conversation responsiveness, and everyday navigation.

## New Features

- **Model-aware reasoning controls.** Model Settings and conversation controls share reasoning presets tailored to the configured model.
- **Consistent research views.** Research figures and interactive views share the app's visual language, with verified source excerpts and saved view state.
- **Direct Library imports.** Import papers from the Library's folder and blank-area context menus.

## Improvements

- **Responsive conversations and Knowledge.** Reduce repeated work in session lists, streamed answers, and Knowledge graph updates.
- **Results for the papers you selected.** View results opens the relevant papers in Cards or Graph mode and focuses a single paper's root card.
- **Recoverable Knowledge processing.** Eligible saved tasks continue after restarting. Recoverable failures retry when dependencies are available, preserving processing settings, completed Knowledge, and each task's retry budget.

## Bug Fixes

- **Workspace reliability.** Prevent concurrent app instances from opening the same workspace and preserve SQLite transaction locks during catalog identity checks.
- **Clearer Knowledge failures.** Recover from temporary startup failures, settle failed supplements and reprocessing rounds correctly, and use consistent retry controls and localized messages.
- **Question editing and navigation.** Restore edit and retry actions on failed or stopped Mentor answers; correct sidebar hover, organization dialogs, onboarding navigation, and permission controls.
- **Available model groups.** Preserve usable Dogzee groups when an optional key-name update cannot be completed.
- **Research Assistant reliability.** Improve attachment access, project resource operations, command dependencies, and isolated command caches.

- **Zotero metadata and folders.** Resolve imported identifiers or titles, retain imported values when no verified result is available, preserve user edits, and organize destination menus by folder hierarchy.
- **Floating panel scrolling.** Keep wheel input inside the hovered island, including its header and padding, without scrolling the page behind it.

## Download and installation

For Apple silicon Macs running macOS 14.6 or later. [Download aPaper 0.1.1](https://github.com/YociLam/aPaper/releases/download/v0.1.1-b1007/aPaper.dmg), open the DMG, and drag aPaper to Applications.

For a manual upgrade, save your work and quit aPaper before replacing the app. See the [installation guide](https://github.com/YociLam/aPaper/blob/main/INSTALL.md) for detailed steps and help with macOS prompts.

## Full changelog

See the [complete change history](https://github.com/YociLam/aPaper/blob/main/CHANGELOG.md).
