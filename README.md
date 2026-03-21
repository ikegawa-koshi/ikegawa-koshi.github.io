# ikegawa-koshi.github.io

池川航史のポートフォリオサイト。

https://ikegawa-koshi.github.io/

## 技術スタック

- [Hugo](https://gohugo.io/) v0.158.0
- [Tailwind CSS](https://tailwindcss.com/) v4
- GitHub Pages（GitHub Actions でデプロイ）

## ローカル開発

```bash
# 依存パッケージのインストール
npm install

# 開発サーバー起動
hugo server
```

## ディレクトリ構成

```
├── assets/css/        # Tailwind CSS
├── config/_default/   # Hugo 設定ファイル
├── content/           # コンテンツ（Markdown）
│   ├── authors/       # プロフィール
│   ├── experience.md  # 経歴
│   ├── oss/           # OSS 貢献
│   ├── patents/       # 特許
│   └── publication/   # 学術文献
├── data/              # データファイル（YAML）
│   ├── publications.yaml
│   ├── patents.yaml
│   └── oss.yaml
├── layouts/           # テンプレート
└── static/            # 静的ファイル（PDF 等）
```

## ライセンス

[LICENSE.md](LICENSE.md) を参照。
