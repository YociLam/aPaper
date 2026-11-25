# aPaper 0.1.4

[English](https://github.com/YociLam/aPaper/blob/main/releases/0.1.4/en.md) · [简体中文](https://github.com/YociLam/aPaper/blob/main/releases/0.1.4/zh-Hans.md) · [繁體中文](https://github.com/YociLam/aPaper/blob/main/releases/0.1.4/zh-Hant.md) · [日本語](https://github.com/YociLam/aPaper/blob/main/releases/0.1.4/ja.md) · [한국어](https://github.com/YociLam/aPaper/blob/main/releases/0.1.4/ko.md)

這次更新讓你可以稍後再讀通知，在較窄的視窗中繼續閱讀，並在重新開啟主視窗時回到研究工作區。

## 新功能

- **圖文通知**　通知可依用戶端與介面語言發送。面板支援格式化文字、圖片、連結與操作按鈕，影片連結會在瀏覽器中開啟。
- **稍後閱讀**　使用中收到訊息時，靈動島會短暫提醒。點選提醒或右下角的鈴鐺即可閱讀；有更新按鈕時，鈴鐺會顯示在其上方。已快取的未讀訊息會在下次啟動時開啟，離線也能查看。讀過一則訊息不會影響後續通知。
- **社群入口**　簡體中文與繁體中文介面的「關於」頁新增 aPaper QQ 群邀請和 QR 碼。

## 使用體驗改進

- **窄視窗閱讀**　縮窄視窗時，先收起左側文獻欄，再從雙欄閱讀切換為單欄，最後收起右側面板。拉寬後會依相反順序恢復原先開啟的欄位與閱讀模式，動畫與手動操作一致。
- **二狗子預設模型**　論文導師、研究助手與知識管家預設使用 GPT 6.2 Sol，推理強度為中等。

## 問題修正

- **長訊息輸入**　游標停在輸入框內時，可上下捲動草稿，對話記錄保持原位。送出後保留已調整的輸入框高度。
- **工作區復原**　從 Dock 或快捷研究重新開啟主視窗時，會恢復工作區與通知入口。即使個別助手的選用設定安裝或驗證失敗，仍可進入工作區。
- **推理級別相容性**　模型服務拒絕所選推理級別時，aPaper 會在同一模型上嘗試其他支援的級別，並記住首次成功的選擇，供後續同類請求使用。

## 下載與安裝

0.1.1、0.1.2 與 0.1.3 皆可直接差分更新至 0.1.4。差分套件不適用時可使用完整更新套件。0.1.0 請使用下方 DMG 手動更新。

在配備 Apple 晶片且執行 macOS 14.6 或更新版本的 Mac 上，[下載 DMG](https://github.com/YociLam/aPaper/releases/download/v0.1.4-b1010/aPaper.dmg)，開啟後將 aPaper 拖入「應用程式」。手動升級時請先結束 aPaper，再取代舊版本。參閱[安裝指南](https://github.com/YociLam/aPaper/blob/main/INSTALL.md)。

## 完整更新記錄

查看[版本歷程](https://github.com/YociLam/aPaper/blob/main/CHANGELOG.md)。
