# aPaper 0.1.1

[English](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/en.md) · [简体中文](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/zh-Hans.md) · [繁體中文](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/zh-Hant.md) · [日本語](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/ja.md) · [한국어](https://github.com/YociLam/aPaper/blob/main/releases/0.1.1/ko.md)


## 新機能
- モデル設定と会話の入力欄で、モデルに応じた推論強度のプリセットを共通化。
- 研究図表とインタラクティブ表示のデザインを統一。検証済みの出典抜粋と表示状態の保存に対応。
- Library のコンテキストメニューから論文を直接インポート可能に。

## 改善
- 会話一覧、ストリーミング回答、Knowledge グラフ更新の応答性を改善。
- 結果表示で、操作対象の論文をカードまたはグラフに表示。
- 再起動後に継続可能な保存済み Knowledge タスクを再開。依存機能が利用可能になると回復可能な失敗を再試行し、処理設定と既存の知識を保持。

## 修正
- 同じワークスペースを複数の App が同時に開くことを防ぎ、SQLite のトランザクションロックを保持。
- Knowledge 起動時の一時的な失敗に、回数を制限した復旧処理と明確な案内を追加。
- 失敗または停止した Mentor 回答で、質問の編集と再試行を復元。
- サイドバーのホバー展開、整理ダイアログ、初期設定の移動と許可ボタンを修正。
- 任意のキー名更新に失敗しても、利用可能な Dogzee モデルグループを保持。
- Research Assistant の添付ファイルへのアクセス、プロジェクト操作とコマンド実行の信頼性を改善。
- Zotero の識別子やタイトルからメタデータを照合し、ユーザーの編集を保持。
- 移動先とコピー先を階層化したフォルダメニューで表示。
- フローティングパネルの見出しや端でも、ホバー中のパネル内でスクロール。

[変更履歴](https://github.com/YociLam/aPaper/blob/main/CHANGELOG.md)
