### docker-datadog
dockerコンテナのボリュームマウントを使用した、datadog log collectionのユースケース
https://docs.datadoghq.com/ja/logs/log_collection/
- コンテナに出力されたログのみをDatadogで監視し、アラートを出す想定（Log Management Plan）
- 標準出力は監視対象とせず、ホストで集約し、S3等のストレージに定期的にアップロードする

# Dependency
- Docker Desktop Community Version 2.0.0.3 (31259)

# Setup
- .envにDatadogのAPIキーを設定
- docker-compose起動
# Setup
`docker-compose up -d`

