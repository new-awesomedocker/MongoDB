# MongoDB
MongoDB sample DB



## run mongoDB by bash

```sh
docker exec -it mongo bash
```

then

```sh
mongosh
```


# 日本語


## MongoDBとは

OSSなドキュメントデータベースのこと。
json形式でデータを保存することができる。

## 実行方法

ソースコード取得

```sh
git clone https://github.com/new-awesomedocker/MongoDB.git
```

移動

```sh
cd MongoDB
```

コンテナ起動

```sh
docker-compose up -d
```

コンテナ内部に入る。

```sh
docker exec -it mongo bash
```

mongoshの起動確認→完了

```sh
mongosh
```







