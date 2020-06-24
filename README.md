cloud-run-integratoin-sample
---

Cloud Run と GitHub をインテグレーションして、自動的にCloud Runにデプロイするサンプルです。  
ミニマムな構成。

## ファイル類の説明

### www ディレクトリ

外部に公開されるディレクトリです。  
このディレクトリ内に配置されたものが nginx から公開されます。

### www/index.html

公開したいメインのコンテンツ(HTML)ファイルです。  

### default.conf

nginx の config です。

### Dockerfile

コンテンツを公開する nginx のコンテナを生成します
