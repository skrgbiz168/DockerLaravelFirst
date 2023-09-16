## 本プログラムについて
Docker-composerを使用して、laravel10の構築を行いました

ただ、npm run dev状態でページを更新に1分近く時間を要するため、開発は保留にする

## 参考ページ
[Laravel 10 の開発環境をdockerで実現する方法](https://qiita.com/hitotch/items/869070c3a9f474a358ea)

## 変更箇所
- docker-compose.ymlのl10devをreserveに書き換える
- docker\nginx\default.confのrootを/src/www/publicにする
- docker\php\DockerfileのNODE_VERSION=18.17.1にする(最新バージョン)

