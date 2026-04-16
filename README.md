# CertGen - 批量榮譽證書可定製化生成系統

純靜態單檔 HTML 證書生成器，無需伺服器、無需登入、資料不上傳，開箱即用。

## 功能

- 高度可定製的證書模板，支援變數替換（`{name}` `{org}` `{title}` 等）
- 批量生成 PDF，所見即所得（html2canvas 截圖方案）
- SHA-256 防偽指紋 + 浮水印
- CSV 匯入名單
- 名單公示頁生成
- 純本地運行，雙擊 `index.html` 即可使用

## 使用方式

1. 打開 `cert-generator/index.html`
2. 填寫機構名稱、證書類型、正文模板等
3. 輸入姓名或匯入 CSV
4. 點擊「載入名單」→ 預覽 → 生成 PDF

## 專案結構

```
cert-generator/
├── index.html   — 完整應用（單檔）
└── sample.csv   — 範例名單
```

## 授權

MIT License

---

# CertGen - Batch Certificate Generator

A pure static single-file HTML certificate generator. No server, no login, no data upload — just open and use.

## Features

- Highly customizable certificate template with variable placeholders
- Batch PDF generation (WYSIWYG via html2canvas)
- SHA-256 anti-forgery fingerprint + watermark
- CSV import
- Roster page generation
- Runs entirely in the browser — double-click `index.html` to start

## Usage

1. Open `cert-generator/index.html`
2. Fill in organization name, certificate type, body template, etc.
3. Enter names or import a CSV file
4. Click "Load Names" → Preview → Generate PDF

## Project Structure

```
cert-generator/
├── index.html   — Full application (single file)
└── sample.csv   — Sample name list
```

## License

MIT License

---

# CertGen - 一括証明書カスタマイズ生成システム

サーバー不要・ログイン不要・データアップロードなし。純粋な静的 HTML 単一ファイルの証明書ジェネレーターです。

## 機能

- 高度にカスタマイズ可能なテンプレート（`{name}` `{org}` `{title}` 等の変数対応）
- 一括 PDF 生成（html2canvas による WYSIWYG）
- SHA-256 偽造防止フィンガープリント + 透かし
- CSV インポート対応
- 名簿一覧ページの生成
- ブラウザのみで動作 — `index.html` をダブルクリックするだけ

## 使い方

1. `cert-generator/index.html` を開く
2. 組織名・証明書タイプ・本文テンプレートなどを入力
3. 氏名を入力、または CSV をインポート
4. 「名簿読み込み」→ プレビュー → PDF 生成

## プロジェクト構成

```
cert-generator/
├── index.html   — アプリケーション全体（単一ファイル）
└── sample.csv   — サンプル名簿
```

## ライセンス

MIT License
