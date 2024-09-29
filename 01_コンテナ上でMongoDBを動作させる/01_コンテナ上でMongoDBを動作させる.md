# MongoDBとは
NoSQLデータベース (ドキュメント指向)
スキーマ（スキーマレス）、JSON形式（BSONとして保存）でのデータ保存
非構造化データに強み、チャット、メッセージングアプリ、特にIoTデータに有効


# 01_コンテナ上でMongoDBを動作させる
docker-compose up -d

Wiredtiger：アクセス権限がないとエラーが出たとき
sudo chown -R $(id -u):$(id -g) ./data/db