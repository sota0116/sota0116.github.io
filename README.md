# 制作サンプル集（jutaku-samples）

受託事業 Phase 0 のポートフォリオ用サンプルサイト。

| ファイル | 内容 |
|---|---|
| `index.html` | ポートフォリオ索引ページ（3サイトへのリンク） |
| `site1/index.html` | 小規模店舗LP（ベーカリー＆カフェ「Bakery Aoi」） |
| `site2/index.html` | コーポレートサイト（工務店「高橋工務店」） |
| `site3/index.html` | サービス紹介サイト（パーソナルジム「Studio K」） |

各サイトとも単一HTMLファイル完結（外部画像・外部フォントなし）。掲載内容はすべて架空で、フッターに「※これは制作サンプルです」と明記済み。

## GitHub Pages への公開手順（sota0116 アカウント想定）

1. GitHub で新規リポジトリを作成する（例：`portfolio-samples`、Public）。
2. このフォルダの中身をリポジトリのルートにアップロードする。
   - Web画面から：リポジトリで「Add file → Upload files」に `index.html` と `site1` `site2` `site3` フォルダごとドラッグ＆ドロップし、コミット。
   - または git コマンドで push する。
3. リポジトリの **Settings → Pages** を開き、Source を「Deploy from a branch」、Branch を `main` / `(root)` に設定して Save。
4. 数分待つと公開される。URL は次の形式：
   - 索引ページ：`https://sota0116.github.io/portfolio-samples/`
   - 各サイト：`https://sota0116.github.io/portfolio-samples/site1/` など
5. 公開できたら、このURLをクラウドワークス／ココナラのプロフィールや応募文のポートフォリオ欄に貼る。
