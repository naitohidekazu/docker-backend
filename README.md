# docker-backend
バックエンドの環境

## srcにlaravelを構築
### コンテナに入る
docker-compose exec app bash

### gitkeepファイルを削除

### appコンテナに入って、以下を実行
composer create-project --prefer-dist laravel/laravel . "7.*"

## xdebug
pecl install xdebug && docker-php-ext-enable xdebug
