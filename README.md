# Rails チュートリアル - Toy App
個人勉強用リポジトリ（過去に TIL でやっていたコードを移行）

教材出典：[Ruby on Rails チュートリアル 第4版](https://railstutorial.jp/chapters/beginning?version=5.1) 第1章～第2章

## 環境
- Ruby：2.5.5
- Rails：5.2.4.4

## Docker 環境立ち上げ
コンテナ立ち上げ
```
$ docker-compose up -d
```

DB 作成とマイグレーション（初回のみ）
```
$ docker-compose exec web rails db:create db:migrate
```

localhost:3000 にアクセス