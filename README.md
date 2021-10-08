# docker
1. コンテナ立ち上げ
```
$ docker-compose up -d --build
```

2. コンテナを起動
```sh:up
$ docker-compose up -d
```

3. ポート番号80へアクセス：[localhost](http://localhost:8000/)

* コンテナ内に入る
```sh:exec
$ docker-compose exec django bash
```
* コンテナを削除
```sh:down
$ docker-compose down
```