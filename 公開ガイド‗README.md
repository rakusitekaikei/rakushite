# ラクシテHP｜公開ガイド（GitHub Pages / 無料）

## 公開後のURL
```
https://rakusitekaikei.github.io/rakushite/
```
このURLに合わせて、ファイル内のSEO設定（canonical、OGP、構造化データ、sitemap.xml、robots.txt）はすべて更新済みです。

**注意：リポジトリ名は必ず `rakushite` にしてください。** 別の名前にすると、URLの `/rakushite/` の部分が変わってしまい、ファイル内の設定とズレてしまいます（その場合は教えてください、書き換えます）。

## 公開手順（無料・課金なし）

1. GitHubで新しいリポジトリを作成
   - Repository name：`rakushite`
   - Public を選択 → 「Create repository」

2. このZIPを解凍し、中身（`index.html`や`images`フォルダなど）を全部
   リポジトリの「Add file」→「Upload files」でアップロード → 「Commit changes」

3. リポジトリの「Settings」→左メニュー「Pages」→ Branch を `main` にして「Save」

4. 数分待つと `https://rakusitekaikei.github.io/rakushite/` で公開されます

## お金がかかる部分について
このガイドの方法（GitHub Pages）は完全無料です。今回の一式には課金が発生する要素は含まれていません。
将来的に `rakushite.jp` のような独自ドメインが欲しくなった場合のみ、ドメイン取得費（年1,000〜3,000円程度）が発生します。今は不要です。

## 公開後にやると良いこと（すべて無料）
- Googleサーチコンソール（https://search.google.com/search-console）に登録し、上記URLとsitemap.xml（`https://rakusitekaikei.github.io/rakushite/sitemap.xml`）を送信すると、Googleに早く認識されます。

## 公開前に必ず確認
`tokushoho.html`（特定商取引法に基づく表示）の中で【ご確認ください】と書いた3項目（お支払い方法／お支払い時期／キャンセル・返品について）は、実際の運用内容に合わせて書き換えてください。

## ファイル構成
```
index.html          … トップページ
bookkeeping.html     … 記帳代行ページ
development.html     … アプリ・ソフト開発ページ
tokushoho.html        … 特定商取引法に基づく表示
robots.txt / sitemap.xml … 検索エンジン向け設定
images/               … ロゴ・QRコード・favicon・OGP画像
```
