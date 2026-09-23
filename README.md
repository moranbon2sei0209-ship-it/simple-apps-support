# Simple Apps サポートサイト

Simple AppsのiOSアプリ向けサポート・プライバシー情報を掲載する静的サイトです。現在はSimpleRecordを掲載しています。

GitHub Pagesで `main` ブランチの `/(root)` から配信する想定です。HTMLとCSSのみで動作し、ビルドや外部依存はありません。リンクはプロジェクトサイト `/simple-apps-support/` に対応する相対パスです。

- `index.html`：トップページ
- `styles.css`：共通スタイル
- `simplerecord/index.html`：機能・FAQ・お問い合わせ
- `simplerecord/privacy.html`：プライバシーポリシー

## 公開前の確認

両方のSimpleRecordページにある `CONTACT_EMAIL_PLACEHOLDER` を正式な連絡先に置き換え、「お問い合わせ先は準備中です。」も更新してください。App Store申請前に対応が必要です。

プライバシー文面は提供された仕様と、ローカルのSimpleRecordソース（Record.swift、AttachmentStore.swift、ExportView.swift、SimpleRecordApp.swift、Xcodeプロジェクト設定）の確認に基づきます。CloudKit不使用は提供仕様に基づき、外部パッケージの参照も確認した範囲ではありません。解析・広告・追跡・サーバー送信・暗号化・バックアップや共有先のデータ処理については断定していません。公開前に配布版の実装と文面の一致、および無料期間・買い切りの案内を確認してください。
