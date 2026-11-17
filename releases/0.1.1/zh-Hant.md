# aPaper 0.1.1

[English](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/en.md) · [简体中文](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/zh-Hans.md) · [繁體中文](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/zh-Hant.md) · [日本語](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/ja.md) · [한국어](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/ko.md)


## 新功能
- 模型設定與對話輸入框統一採用各模型的推理強度預設。
- 研究圖表與互動檢視採用一致樣式，支援已核驗的來源摘錄與檢視狀態保存。
- 可直接從資料庫右鍵選單匯入論文。

## 改進
- 改善對話清單、串流回答與知識圖譜更新的回應表現。
- 查看結果可在卡片或圖譜模式中定位本次操作的論文。
- 重新啟動後接續符合條件的已儲存沉澱工作；依賴項目恢復可用時，自動重試可恢復的錯誤，保留處理設定與既有知識。

## 問題修復
- 防止多個 App 執行個體同時開啟同一工作區，並保留 SQLite 交易鎖定。
- 為知識庫啟動時的短暫失敗提供有限恢復與清楚提示。
- 恢復回答失敗或停止後的問題編輯與重試。
- 修正側邊欄懸停展開、整理對話框、引導頁導覽與授權控制項。
- 保留可用的 Dogzee 模型群組，避免選用的金鑰名稱更新失敗造成群組消失。
- 改善研究助理的附件存取、專案資源操作與命令執行可靠性。
- 使用 Zotero 既有識別碼或標題整理中繼資料，並保留使用者編輯。
- 移動到與複製到選單依資料夾層級展開。
- 游標停留於靈動島時，捲動維持在島內，涵蓋標題與邊緣區域。

## 下載與安裝

[下載 macOS 版](https://github.com/YociLam/aPaper/releases/download/v0.1.1-b1007/aPaper.dmg) · [安裝指南](https://github.com/YociLam/aPaper/blob/main/INSTALL.md)

## 完整更新日誌

[查看所有版本的更新紀錄](https://github.com/YociLam/aPaper/blob/main/CHANGELOG.md)。
