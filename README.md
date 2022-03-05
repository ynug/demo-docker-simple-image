# シンプルなDockerイメージの作成

実行すると `Hello World!` と表示される。

下記記事のサンプルプログラム  
https://zenn.dev/ynug/articles/docker-image-extraction

## イメージのビルド方法

`docker build -t yngu/demo-docker-simple-image:1.0 docker --no-cache`

## ビルドしたイメージの実行方法

`docker run --rm yngu/demo-docker-simple-image:1.0`

## dockerhub

https://hub.docker.com/r/yngu/demo-docker-simple-image