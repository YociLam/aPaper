# Release notes guide

GitHub Releases uses the English body. Put translations in `releases/<version>/<locale>.md` (`en`, `zh-Hans`, `zh-Hant`, `ja`, `ko`), each with the same language navigation. Publish those files before linking them from the Release. Use absolute GitHub document links in the Release body; relative links are fine within the documents.

For a first release, introduce the product and its purpose, explain the complete core workflow, describe choices that matter to users, and finish with getting started and actual system requirements. [aPaper 0.1.0](0.1.0/en.md) is the launch example.

For later updates, use the template below. Keep only sections that have real changes. Lead with the most useful changes, use bold feature labels and explain the result for the user. Include known issues or required migration steps only when applicable. Link a full changelog only when a real public changelog exists; never invent counts, issue numbers, or links to private source.

Do not include internal build numbers, hashes, feed paths, signing receipts, development chores, or repeated translations in the body. Preserve technical metadata in the release record. Alpha/Beta labels belong in the release title and summary when applicable.

---

English · [简体中文](https://github.com/YociLam/aPaper/blob/main/releases/<version>/zh-Hans.md) · [繁體中文](https://github.com/YociLam/aPaper/blob/main/releases/<version>/zh-Hant.md) · [日本語](https://github.com/YociLam/aPaper/blob/main/releases/<version>/ja.md) · [한국어](https://github.com/YociLam/aPaper/blob/main/releases/<version>/ko.md)

<One short paragraph explaining the focus of this update.>

## New Features

- **<Feature>.** <What users can now do and why it helps.>

## Improvements

- **<Area>.** <The observable improvement.>

## Bug Fixes

- Fixed <the problem users encountered and when it occurred>.

## Getting Started

[Download aPaper](<verified-installer-url>) · [Installation guide](https://github.com/YociLam/aPaper/blob/main/INSTALL.md) · [Feedback](https://github.com/YociLam/aPaper/issues)
