# easy-mysql
超絶簡単にMySqlを構築できちゃうdocker-compose

## 使い方

### 起動

```bash
$ docker-compose up
```

### 初期化

DBの初期化に関しては`db/data/init`直下に入っています

## 注意

このcomposeはテスト用に構築するmysqlを想定しています。つまり、セキュリティだのなんだのは考慮してないということです。
