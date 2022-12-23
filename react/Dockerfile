FROM node:alpine
# ワーキングディレクトリを作成
WORKDIR /work
# アプリケーションの依存関係をインストールする
COPY package*.json ./
# RUN npx create-react-app /my-app
# アプリケーションのソースをバンドル
COPY . .