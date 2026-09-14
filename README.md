# アシスタント勤怠・制作ポータル (Manga Assistant Portal)

漫画制作現場向けのアシスタント勤怠打刻・進捗管理フォームと、運用マニュアルを統合したWebポータルサイトです。GitHub Pagesを利用してホスティングしています。

## 📌 概要
Google Apps Script (GAS) で構築した勤怠・成果管理フォームを埋め込み、Google特有の注意バナーを回避してスマートフォンのホーム画面追加（PWA風）にも対応した実務用ポータルです。

- **勤怠・進捗フォーム**: 時給打刻、枠サイズ別のコマ給申請、クリップボードからの画像添付（Ctrl+V）に対応。
- **マニュアル・FAQ一体型**: 深夜シフトの扱い、打刻忘れ時の手動修正ルール、スマホでの利用手順を1画面に集約。
- **レスポンシブデザイン**: PCの作業環境はもちろん、スマートフォンの画面サイズにも完全対応。

## 🛠 技術構成
- **フロントエンド（ポータル）**: HTML5, CSS3, JavaScript
- **ホスティング**: GitHub Pages
- **バックエンド（フォーム・集計）**: Google Apps Script (GAS), Google Spreadsheets
- **通知・連携**: Discord Webhook API, Google Drive API

## 📱 サイトURL
GitHub Pagesにて稼働中：
`https://github.com/addiction04140116-boop/manga-portal`
