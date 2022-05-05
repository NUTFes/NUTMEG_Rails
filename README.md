# Ruby on Rails with Docker
## 環境構築の手順

下記のコマンドを実行  
```
git clone git@github.com:NUTFes/NUTMEG_Rails.git
docker compose build
docker compose run --rm web bundle install
docker compose run --rm web rails db^:create
docker compose run --rm web rails db^:migrate
``` 

