postgres への接続

1. db-work ディレクトリに移動する。
2. docker-compose up -d でコンテナを起動する。
3. docker-compose exec postgres bash で postgres のコンテナに入る。
4. psql -h localhost -U postgres -d postgres で postgres スキーマに接続する。
