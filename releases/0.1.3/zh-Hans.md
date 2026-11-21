# aPaper 0.1.3

[English](en.md) · [简体中文](zh-Hans.md) · [繁體中文](zh-Hant.md) · [日本語](ja.md) · [한국어](ko.md)

aPaper 0.1.3 让更新流程更安全、首次设置更稳定，并改进了二狗子账号恢复和快捷研究快捷键。

## 更新与设置

- 更新弹窗显示实际将要下载的包大小，包括所选差分包。
- 下载前跳过已知不兼容的差分包，同时保留全量包作为回退；读取含结构化差分元数据的更新清单时不再崩溃。
- 只有点击「授权」后才请求访问「文稿」；已有权限则跳过。语言选择保存在工作区之外，更换工作区不会重新开始语言设置。
- 菜单栏快捷研究快捷键控件根据文字自适应宽度，不再留下过多空白。

## 二狗子账号恢复

- 本地凭据缺失时，从已登录账号绑定中恢复二狗子管理令牌，避免重复登录耗尽账号令牌额度。
- 修复账号服务返回可选绑定时的二狗子令牌恢复路径。

## 下载与安装

在 macOS 14.6 或更高版本的 Apple 芯片 Mac 上，[下载 DMG](https://github.com/YociLam/aPaper/releases/download/v0.1.3-b1009/aPaper.dmg)，打开后将 aPaper 拖入 Applications。手动更新时，请退出 aPaper 并替换 Applications 中的旧版本。详情请参阅[安装指南](https://github.com/YociLam/aPaper/blob/main/INSTALL.md)。

## 完整变更记录

完整变更请参阅[CHANGELOG.md](https://github.com/YociLam/aPaper/blob/main/CHANGELOG.md)。
