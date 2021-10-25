# s3-deploy-test
GitHub Actions を使ってAWS S3 静的ホスティングの自動デプロイテスト

## やりたいこと
- 特定のブランチを`git push` した際に開発環境のS3へsync
- プルリクをmaster ブランチにマージで本番環境のS3へsync
