# 概要

docker compose を使った開発環境の構築のテストのためのディレクトリ

## 使用方法

`git clone` をして下記コマンドを実行

```bash
docker compose up -d --build
```

localhost:4000とlocalhost:3000でそれぞれreactとrailsの初期画面が表示されれば成功

frontend : [localhost:4000](http://localhost:4000/)  
backendd : [localhost:3000](http://localhost:3000/)
