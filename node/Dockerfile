# ベースイメージを指定
FROM node:9.11.2-alpine

# node.js の環境変数を定義する
# 本番環境では production
ENV NODE_ENV=development

# 雛形を生成するのに必要なパッケージのインストール
RUN npm install vue-cli -g

# ディレクトリを移動する
WORKDIR /app

# ポート3000番を開放する
EXPOSE 3000