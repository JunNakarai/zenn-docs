# ベースイメージ
FROM node:18-bullseye

# 必要なツールをインストール
RUN apt-get update && apt-get install -y \
    git \
    curl \
    && apt-get clean

# Zenn CLIをインストール
RUN npm install -g zenn-cli

# 作業ディレクトリを設定
WORKDIR /workspace
