# TikTok App Review site

静的HTMLのみの審査用ページです。GitHub Pages等へ配置できます。公開前に運営者の連絡先メールアドレスを `contact.html` に追記し、GitHubリポジトリをPublic Pagesとして公開してください。

リポジトリのPages設定は `.github/workflows/tiktok-pages.yml` が行います。リポジトリ作成後、Actionsの初回実行で公開されます。

推奨Redirect URI（OAuth callback実装後）: `https://<github-user>.github.io/<repo>/oauth/tiktok/callback`
