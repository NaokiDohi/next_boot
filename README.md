# React-Docker

##　実行には下記コマンドを実行

1.  docker-compose build
2.  docker-compose run --rm node sh -c "npx create-next-app frontend"
<!-- 2.
    docker-compose run --rm node sh -c "yarn create next-app frontend"
3.  docker-compose run --rm node sh -c "yarn add create-next-app && npx create-next-app frontend"
4.  docker-compose run --rm node sh -c "npm install -g create-next-app && npx create-next-app ." こちらでは権限関係でエラーが発生 -->
5.  docker-compose run --rm node sh -c "cd frontend && npx create-next-app frontend"
6.  docker-compose run --rm node sh -c "cd frontend && npm install -D tailwindcss@latest postcss@latest autoprefixer@latest"
7.  docker-compose run --rm node sh -c "cd frontend && npx tailwindcss init -p"
8.  docker-compose up -d
9.  docker-compose down
