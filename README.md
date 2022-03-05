# シンプルなDockerイメージの作成

実行すると `Hello World!` と表示される。

下記記事のサンプルプログラム
https://zenn.dev/ynug/articles/docker-image-extraction

## イメージのビルド方法

`docker build -t yuna/hello:1.0 docker --no-cache`

## ビルドしたイメージの実行方法

`docker run --rm yuna/hello:1.0`
