# aPaper 0.1.3

[English](en.md) · [简体中文](zh-Hans.md) · [繁體中文](zh-Hant.md) · [日本語](ja.md) · [한국어](ko.md)

aPaper 0.1.3 では、アップデートと初回設定の信頼性を高め、Dogzee アカウントの復旧とクイックリサーチのショートカットを改善しました。

## アップデートと設定

- 実際にダウンロードされるパッケージのサイズを表示します。選択された差分にも対応します。
- 既知の非互換な差分はダウンロード前に除外し、完全パッケージをフォールバックとして残します。構造化された差分メタデータで終了する問題も修正しました。
- 「許可」をクリックした後だけ書類フォルダへのアクセスを求め、言語選択を作業領域外に保存します。
- クイックリサーチのショートカットボタンがラベル幅に合うようになりました。

## Dogzee アカウントの復旧

- ローカル資格情報がない場合、ログイン済みアカウントから管理トークンを復旧し、再ログインによるトークン上限到達を防ぎます。
- 任意のアカウントサービスバインディングを使う復旧経路を修正しました。

## ダウンロードとインストール

macOS 14.6 以降の Apple silicon Mac で、[DMG をダウンロード](https://github.com/YociLam/aPaper/releases/download/v0.1.3-b1009/aPaper.dmg)して開き、aPaper を Applications にドラッグします。詳しくは[インストールガイド](https://github.com/YociLam/aPaper/blob/main/INSTALL.md)をご覧ください。

## 完全な変更履歴

完全な変更一覧は[CHANGELOG.md](https://github.com/YociLam/aPaper/blob/main/CHANGELOG.md)をご覧ください。
