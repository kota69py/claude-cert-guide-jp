# Claude Cert Guide JP

Claude Certified Architect (Foundations) の日本語学習ガイドと、スマホ向け **1問1答ドリル** です。

## 公開URL（GitHub Pages）

| ページ | URL |
|--------|-----|
| **1問1答ドリル** | https://kota69py.github.io/claude-cert-guide-jp/drill.html |
| トップ | https://kota69py.github.io/claude-cert-guide-jp/ |
| リポジトリ | https://github.com/kota69py/claude-cert-guide-jp |

スマホではブラウザ（Chrome / Safari）で上記 URL を開いてください。Google ドライブのプレビューでは動きません。

## 初回だけ：GitHub Pages を有効化（1回でOK）

Actions から自動公開するには、リポジトリ管理者が **1回だけ** 次を行ってください。

1. 開く: https://github.com/kota69py/claude-cert-guide-jp/settings/pages
2. **Build and deployment** → **Source** で **GitHub Actions** を選択
3. 保存後、Actions の **Deploy GitHub Pages** が成功するのを待つ
   - 手動再実行: https://github.com/kota69py/claude-cert-guide-jp/actions/workflows/pages.yml

有効化後は push のたびに自動デプロイされます。

## ローカルで再生成

```bash
python3 generate_guide.py   # index.html
python3 generate_drill.py   # drill.html
```

## 主なファイル

- `drill.html` — スマホ向け4択ドリル（単体完結）
- `site.full.b64.p*` — Pages 用に圧縮したサイト本体（Actions が展開）
