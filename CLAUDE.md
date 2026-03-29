# Cyberpunk Trade OS — Claude Code Instructions

## このリポジトリについて
Ken5 Investment Lab の LP + ブログサイト。
GitHub Pages で配信。URL: https://ken5investmentlab.github.io/cyberpunk-trade-os/

## ファイル構成
```
index.html                          ← LP本体（触るときは慎重に）
blog/
  index.html                        ← ブログ一覧
  [slug]/index.html                 ← 各記事
sitemap.xml                         ← 記事追加のたびに更新する
robots.txt
google8b4f3b8ed9a7759a.html        ← 削除禁止
```

---

## ブログ記事を追加するときのルール

### デザイン
- LP（index.html）のCSS変数・フォント・背景グリッドを必ず踏襲する
- `--primary: #00f3ff` / `--membership: #bd00ff` / `--discord: #5865F2`
- フォント: Orbitron（見出し）/ Inter（本文）
- 記事テンプレートは `blog/how-to-stop-hesitating-when-trading/index.html` を参照

### 記事のSEOルール
- `<title>`: `[記事タイトル] | Ken5 Investment Lab`
- `<meta name="description">`: 150字以内
- OGPタグ（og:title / og:description / og:url）を必ず入れる
- `<link rel="canonical">` を必ず入れる
- H1にメインキーワードを含める
- 本文冒頭100wordsにキーワードを自然に挿入
- CTAは必ずDiscordリンク: https://discord.gg/JNQEbP5gKE

### ブランドトーン
- ミニマル・自信あり・ハイプなし（Notion/Linear的なトーン）
- ペイン: 「迷い」「ノイズ」「構造のなさ」
- ポジショニング: Cyberpunk Trade OS は「ツール」ではなく「思考の枠組み」
- NG: 「稼げる」「爆益」「必勝」「NISA」「日本株」「仮想通貨」
- ターゲット: 英語圏のTradingViewユーザー

### 記事追加後に必ずやること
1. `blog/index.html` に新記事のカードを追加
2. `index.html` の "Latest from the Lab" セクションを最新3本に更新
3. `sitemap.xml` に新記事のURLを追加
4. git add / commit / push

---

## サイト情報
- Discord: https://discord.gg/JNQEbP5gKE
- X: https://x.com/ken5investlab
- インジケーター: FVN（Fundamental Value Nexus）、SVSI（Smooth Volume Strength Index）
- プラン: Lite / Full Access / Genesis（Whop）
