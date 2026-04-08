# Widen Gsheets Comments Extension

Google スプレッドシートのコメントウィンドウを横幅広げる Chrome 拡張機能

## 機能

- **コメントウィンドウの横幅拡張**: コメントウィンドウをビューポート幅の 40% に拡大します（最小 280px）
- **はみ出し防止**: コメントウィンドウが画面右端を超えた場合、自動で `left` 位置を補正します
- **iframe 対応**: Google スプレッドシート内の iframe にもスタイルを注入します
- **動的コンテンツ対応**: MutationObserver を使用し、後から追加されるコメントウィンドウにも自動で適用します

## インストール

1. このリポジトリをクローンまたはダウンロードします
2. Chrome で `chrome://extensions` を開きます
3. 右上の「デベロッパーモード」を有効にします
4. 「パッケージ化されていない拡張機能を読み込む」をクリックし、このリポジトリのフォルダを選択します

## 対応 URL

`https://docs.google.com/spreadsheets/*`

## ライセンス

[MIT LICENSE](LICENSE)
