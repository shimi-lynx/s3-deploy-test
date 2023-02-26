# s3-deploy-test
GitHub Actions を使ってAWS S3 静的ホスティングの自動デプロイを行い、GitHub Actions の使い方を学ぶ為のリポジトリ

## やったこと
- 特定のブランチを`git push`で発火、`aws s3 sync`を実行し開発環境のS3にsyncする
- プルリクをmaster ブランチにマージで発火、`aws s3 sync`を実行し本番環境のS3へsyncする
