# aPaper 0.1.3

[English](en.md) · [简体中文](zh-Hans.md) · [繁體中文](zh-Hant.md) · [日本語](ja.md) · [한국어](ko.md)

aPaper 0.1.3 讓更新流程更安全、初次設定更穩定，並改善二狗子帳號復原與快速研究快速鍵。

## 更新與設定

- 更新視窗顯示實際將下載的套件大小，包括所選差分套件。
- 下載前略過已知不相容的差分套件，同時保留完整套件作為回退；讀取含結構化差分中繼資料的更新清單時不再崩潰。
- 只有點選「授權」後才要求存取「文件」；已有權限時跳過。語言選擇保存在工作區外，更換工作區不會重新開始語言設定。
- 選單列快速研究快速鍵控制項依文字自適應寬度，不再留下過多空白。

## 二狗子帳號復原

- 本機憑據缺失時，從已登入帳號繫結中復原二狗子管理權杖，避免重複登入耗盡帳號權杖額度。
- 修正帳號服務回傳可選繫結時的二狗子權杖復原路徑。

## 下載與安裝

在 macOS 14.6 或以上版本的 Apple 晶片 Mac 上，[下載 DMG](https://github.com/YociLam/aPaper/releases/download/v0.1.3-b1009/aPaper.dmg)，開啟後將 aPaper 拖入 Applications。手動更新時，請退出 aPaper 並替換 Applications 中的舊版本。詳情請參閱[安裝指南](https://github.com/YociLam/aPaper/blob/main/INSTALL.md)。

## 完整變更記錄

完整變更請參閱[CHANGELOG.md](https://github.com/YociLam/aPaper/blob/main/CHANGELOG.md)。
