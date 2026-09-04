# TikTok App Review site


静的HTMLのみの審査用ページです。GitHub Pages等へ配置できます。公開前に運営者の連絡先メールアドレスを `contact.html` に追記し、GitHubリポジトリをPublic Pagesとして公開してください。


リポジトリのPages設定は `.github/workflows/tiktok-pages.yml` が行います。リポジトリ作成後、Actionsの初回実行で公開されます。


OAuth Redirect URIはGitHub Pagesではなく、Desktopアプリのloopback URL（http://127.0.0.1:8766/callback/）を使用します。

