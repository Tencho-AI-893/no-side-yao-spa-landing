# ノーサイド八尾SPA 施設紹介ページ

このプロジェクトは、ノーサイド八尾SPA施設の紹介ランディングページです。HTML/CSS/JSで実装され、Tailwind CSSを使用しています。

## プレビュー

ブラウザで `index.html` を開いてください。

## デプロイ方法

### GitHub Pages

1. GitHubリポジトリのSettings > Pagesに移動。
2. Sourceを "Deploy from a branch" に設定。
3. Branchを `master` (または `main`), folderを `/ (root)` に設定。
4. Saveをクリック。
5. 数分後に公開URLが表示されます（例: https://tencho-ai-893.github.io/no-side-yao-spa-landing/）。

### Cloudflare Pages

1. Cloudflareアカウントにログイン（https://dash.cloudflare.com/）。
2. Pagesタブに移動し、"Create a project" をクリック。
3. "Connect to Git" を選択し、GitHubを接続（初回は認証が必要）。
4. リポジトリ "no-side-yao-spa-landing" を選択。
5. ビルド設定:
   - Production branch: `master`
   - Build command: （空欄、または `echo "No build required"`）
   - Build output directory: `/` （ルートディレクトリ）
6. "Save and Deploy" をクリック。
7. デプロイが完了すると、公開URLが表示されます（例: https://no-side-yao-spa-landing.pages.dev/）。

### Vercel

1. Vercelにログイン。
2. "New Project" をクリック。
3. GitHubリポジトリをインポート。
4. デプロイ設定はデフォルトでOK。
5. Deployをクリック。
6. 公開URLが生成されます。

## 注意

このページはデモンストレーション用です。実際の連絡先としては機能しません。