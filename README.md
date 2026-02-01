環境構築

Dockerビルド

・git clone git@github.com:takedatsukasa/test_contact-form.git
・docker-compose up -d --build

Laravel環境構築

・docker-compose exec php bash
・composer install
・cp.env.example.env
・php artisan key:generate
・php artisan migrate
・php artisan db:seed

開発環境

・お問い合わせ画面：http://localhost/

使用技術（実行環境）
・PHP 8.4.14
・Laravel 8.83.8
・nginx 1.29.3