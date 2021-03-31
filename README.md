# docker-backend
バックエンドの環境

■srcにlaravelを構築
1.コンテナに入る
docker-compose exec app bash

2.gitkeepファイルを削除

3.appコンテナに入って、以下を実行
composer create-project --prefer-dist laravel/laravel . "7.*"

■xdebug
pecl install xdebug && docker-php-ext-enable xdebug
