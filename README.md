# name
LEMP-8.1

## Overview
LEMP環境。PHPバージョン=8.1

## Version
- wsl2 -d ubuntu-22.04
- Docker version 20.10.21, build baeda1f

## Usage
###### How to Add Application
- アプリケーションはプロジェクト直下のsrcディレクトリに配置する
- infra/nginx/default.confにserverを追加してrootディレクトリにアプリフォルダを指定
- 必要に応じてポート割当する

###### Xdebug
- xdebug用のポート番号
  - 9000