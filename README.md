# Zennの投稿管理用リポジトリ
- mainブランチが更新されると自動でデプロイされる
## 記事の書き方
1. ```npx zenn new:article```コマンドにより、markdownファイルを作成
2. ```npx zenn preview```コマンドでプレビューを開始する
3. publishedオプションがtrueになっている状態で、commit⇒pushすると同期（デプロイ）が開始される  

参考：https://zenn.dev/zenn/articles/zenn-cli-guide
