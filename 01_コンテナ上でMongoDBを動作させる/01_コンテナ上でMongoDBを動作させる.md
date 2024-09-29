# MongoDBとは



# 01_コンテナ上でMongoDBを動作させる
docker-compose up -d

Wiredtiger：アクセス権限がないとエラーが出たとき
sudo chown -R $(id -u):$(id -g) ./data/db