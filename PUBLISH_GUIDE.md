# GameFinder 公開マニュアル

## 1. おすすめの公開方法
最初は GitHub Pages をおすすめします。

理由:
- 静的HTML/CSS/JavaScriptサイトと相性が良い
- 公開リポジトリならGitHub FreeでPagesを利用できる
- `github.io` のURLならHTTPSが自動
- 後から独自ドメインも設定できる

## 2. GitHub Pagesで公開する

### ① GitHubアカウントを作る
GitHub公式サイトからアカウントを作成します。

### ② 新しいリポジトリを作る
例:
`gamefinder`

公開設定は `Public`。

### ③ このZIPの中身をアップロード
ZIPそのものではなく、
`index.html`、`assets/`、`games/` など中身をアップロードします。

### ④ Pagesを有効化
GitHub:
`Settings` → `Pages`

公開元として通常は:
- Branch: `main`
- Folder: `/ (root)`

を選びます。

### ⑤ 公開URLを確認
通常は以下の形式です。

`https://ユーザー名.github.io/gamefinder/`

## 3. 独自ドメイン
サイトがある程度できてからで大丈夫です。

GitHub Pagesは独自ドメインとHTTPSに対応しています。
独自ドメイン購入後、Pages設定とDNS設定を行います。

最初の数週間は無料の `github.io` URLでも問題ありません。

## 4. 公開後に必ず直すもの

### sitemap.xml
現在の `https://example.com/` を、
実際の公開URLへ置換してください。

例:
`https://example.com/games/frostpunk.html`
↓
`https://username.github.io/gamefinder/games/frostpunk.html`

### robots.txt
こちらもSitemap URLを実際のURLに変更します。

## 5. Google検索へ登録
Google Search Consoleでサイトを追加し、
`sitemap.xml` を送信します。

例:
`https://username.github.io/gamefinder/sitemap.xml`

登録してすぐ検索上位になるわけではありません。
Googleがページをクロール・評価するまで時間が必要です。

## 6. 広告表記
アフィリエイトを開始したら、
「このサイトはアフィリエイト広告を利用しています」
など、読者にはっきり分かる表示を維持してください。

GameFinder v5には、
トップページ・運営者情報・プライバシーポリシーへ
広告に関する記載を追加しています。

## 7. 公開後の順番

1. サイト公開
2. 表示確認
3. 運営者情報・プライバシーポリシー確認
4. 10〜20ゲーム掲載
5. 5〜10本の記事掲載
6. Search Console登録
7. アクセスが出始める
8. アフィリエイト提携を検討
9. 記事追加・改善

## 8. ChatGPTに任せる部分
今後は以下をこちらに依頼できます。

- ゲーム追加
- 記事追加
- SEOタイトル改善
- デザイン変更
- 内部リンク追加
- sitemap更新
- アフィリエイトリンク反映
- セール特集追加
- ゲームデータ整理

あなたがコードを書く必要はありません。
