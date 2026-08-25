# GitHubアップロード手順（v6 → v6.1）

## 一番安全な方法
今回のv6.1はサイト構造を維持しているため、GitHub上の全ファイルを削除する必要はありません。

`gamefinder-v6.1-changed-files.zip` を展開し、GitHubの `akaoriax-sys/gamefinder` に同じフォルダ構造のままアップロードしてください。

上書き対象:
- assets/styles.css
- js/main.js
- data/games.json
- games/frostpunk.html
- games/cities-skylines.html
- games/raft.html
- games/satisfactory.html
- games/no-mans-sky.html
- README.md
- CHANGELOG_V6_1.md

同じ名前のファイルは更新としてコミットされます。

## Commit message
`feat: deepen five beginner game guides`
