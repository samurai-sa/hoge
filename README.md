## TypeScript
## シンボリックリンクを貼る
```
docker-compose exec node /bin/bash
cd /usr/local/bin
ln -s /usr/src/app/node_modules/typescript/bin/tsc
```

## コンパイル
```
docker-compose exec node /bin/bash
tsc Typescriptファイル
node JSにコンパイルされたTSファイル
```

## 参考
- https://qiita.com/samurai_se/items/3f5c88719902124b6546
