# Installation / 安装

Use only the versioned `aPaper.dmg` asset from this repository's Releases. Check the published file size and SHA-256 (`shasum -a 256 aPaper.dmg` on macOS). A checksum proves matching bytes, not Apple notarization.

Open the DMG, drag aPaper to Applications, eject the disk image, then launch the installed copy. The minimum is macOS 14.6 on Apple silicon.

The initial distribution is ad-hoc signed and **not notarized by Apple**. macOS may block its first launch. After checking the release's provenance and checksum, use Apple's per-application Open Anyway option in System Settings → Privacy & Security if offered. Do not disable Gatekeeper, remove quarantine globally, or ignore a malware/damaged-app warning. Contact support when the system reports such a warning.

For a later manual update, save your work and quit aPaper before replacing the App. Keep your own backup of research data. An older App is not a database or account rollback tool. A signing-identity change may require normal account reauthentication; never export login tokens or change Keychain access controls to work around it.

请使用本仓库 Releases 中明确版本的 `aPaper.dmg`，核对字节数和 SHA-256。打开磁盘映像，将 aPaper 拖到 Applications，推出映像，再启动已安装副本。首发使用临时签名，未经 Apple 公证；如系统阻止首次启动，核对来源后可使用系统针对单一应用提供的“仍要打开”。不要关闭系统安全保护，也不要忽略恶意软件或应用损坏警告。更新前保存工作并退出应用；软件回退不等于研究数据或云账号回退。
