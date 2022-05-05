# wantedly_2022_summer_intern_ship_task
## 環境構築の手順

下記のコマンドを実行  
```
git clone git@github.com:YushiroDodo63/wantedly_2022_summer_intern_ship_task.git
docker compose build
docker compose run --rm web bundle install
docker compose run --rm web rails db^:create
docker compose run --rm web rails db^:migrate
``` 

