# yo41sawada.github.io

和田 佳久 のポートフォリオサイト。

- **公開URL**: https://yo41sawada.github.io/
- **構成**: 単一の `index.html`（依存ライブラリなし・素の HTML/CSS）
- **ホスティング**: GitHub Pages

## ローカルで確認する

ブラウザで `index.html` を開くだけ。ビルド不要。

```sh
open index.html
```

## 編集する

すべての内容は `index.html` 内に記述されている。セクションは番号付きの `<section>` で区切られており、職務経歴は `<details class="job">` の折りたたみUIになっている。

- ライト/ダークテーマは OS 設定に追従（`prefers-color-scheme`）
- SNS / X のリンクは Contact セクションのプレースホルダを差し替えて追加する

## 注意

職務経歴書（`*.pdf`）は `.gitignore` で除外しており、リポジトリには公開されない。
