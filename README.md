# Claude Cert Guide JP

Claude Certified Architect (Foundations) の日本語学習ガイドと、スマホ向け **1問1答ドリル** です。

## GitHub Pages

| ページ | URL |
|--------|-----|
| **1問1答ドリル** | https://kota69py.github.io/claude-cert-guide-jp/drill.html |
| 学習ガイド | https://kota69py.github.io/claude-cert-guide-jp/ |
| リポジトリ | https://github.com/kota69py/claude-cert-guide-jp |

スマホではブラウザ（Chrome / Safari）で上記 URL を開いてください。Google ドライブのプレビューでは動きません。

## ローカルで再生成

```bash
python3 generate_guide.py   # index.html
python3 generate_drill.py   # drill.html
```

## 主なファイル

- `drill.html` — スマホ向け4択ドリル（単体完結）
- `index.html` — 全30タスク学習ガイド
- `app.js` / `glossary.js` / `sw.js` — ガイド用
- `content_d*.py` — コンテンツ正本
