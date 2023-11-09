# wasm-julia.rs

🧀🧀🧀 RustによるWebAssemblyでジュリア集合を描画するサンプルです！  

## 環境構築

DevContainerに入り、以下のコマンドを実行します。  

```shell
wasm-pack build

cd ./www/
yarn install
yarn start
```

## 本番用実行

```shell
docker build -t my-image .
docker run -d --rm -p 8000:80 --name my-container my-image
```
