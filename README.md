#React_Starter
react.js、Typescript、Dockerによる環境構築テンプレート

###docker-entrypoint.shの権限変更
chmod 755 app/docker-entrypoint.sh

###コンテナイメージ構築 & 起動
docker-compose up --build -d

###起動から画面表示まで多少時間がかかるので以下コマンドで状況を逐次チェック
docker-compose logs react_stater
