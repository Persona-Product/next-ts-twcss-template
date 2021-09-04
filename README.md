# 環境構築
- yarnを使う
- nodeのバージョンは v14.15.1
- nodenvを使うと便利

1. ローカルにクローンする
```git
git clone "URL"
```
2. node_modulesをインストールする
```yarn
yarn install
```
3. 起動
```yarn
yarn dev
```

# json-server起動

1. 起動
```yarn
yarn api
```
2. エンドポイントにアクセス

> http://localhost:3001/posts　　
> http://localhost:3001/comments　　
> http://localhost:3001/profile

3. フロント側で各エンドポイントのAPIを叩くと、src/db/db.jsonに記述したjsonデータを受け取ることができる
