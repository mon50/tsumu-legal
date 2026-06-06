# tsumu-legal

Tsumu アプリの法的情報（プライバシーポリシー / 利用規約 / 特定商取引法に基づく表記）を
GitHub Pages で公開するための静的サイト。

正本（オリジナル）は本体リポジトリ `tsumu` の `docs/legal/` 配下にあり、
本リポジトリの `legal/` はそこからミラーしたもの。

## 公開 URL

| ドキュメント | ja | en |
|---|---|---|
| プライバシーポリシー | `/legal/privacy/ja/` | `/legal/privacy/en/` |
| 利用規約 | `/legal/terms/ja/` | `/legal/terms/en/` |
| 特定商取引法に基づく表記 | `/legal/tokushoho/ja/` | `/legal/tokushoho/en/` |

ベース URL: `https://mon50.github.io/tsumu-legal/`

## 更新手順

1. 本体 `tsumu` 側で `docs/legal/` を編集・レビューする（正本）。
2. 変更を本リポジトリの `legal/` に反映してコミット・push する。

> **注意**: 公開前に各文書内の `<<CONTACT_EMAIL>>` を実際の連絡先メールアドレスへ置換すること。
