# Okayan's Portfolio

Astroで制作したポートフォリオサイトです。プロフィールや制作物、スキル、資格、学習活動を紹介するほか、Journalで日々の学びや振り返りを公開しています。Journalの記事は `src/content/journal/` にMarkdown形式で追加できます。

## 開発方法

```bash
npm install
npm run dev
```

ブラウザで表示されたローカルURLを開くと、開発中のサイトを確認できます。

## 主なコマンド

- `npm run dev` — 開発サーバーを起動
- `npm run build` — 本番用サイトをビルド
- `npm run preview` — Cloudflare Workers上でビルド結果を確認
- `npm run deploy` — Cloudflare Workersへデプロイ

AstroとCloudflare Workersを利用しています。記事のテンプレートは `docs/journal-template.md` を参照してください。
