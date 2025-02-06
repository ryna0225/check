# check
# FashionablyLate(お問い合わせフォーム)

## 環境構築
**Dockerビルド**
1.git@github.com:ryna0225/check.git
2. DockerDesktopアプリを立ち上げる
3.docker-compose up -d --build

*MySQLは、OSによって起動しない場合があるのでそれぞれのPCにあわせてdocker-compose.ymlファイルを編集してください。

Laravel環境構築
1.docker-compose exec php bash
2.composer install
3..env.exampleファイルから.envを作成し、環境変数を変更
4.php artisan key:generate
5.php artisan migrate

使用技術
PHP　8,0
Laravel　10.0
MySQL 8.0

URL
開発環境　http://localhost/
phpMyAdmin:http://localhost:8080/
