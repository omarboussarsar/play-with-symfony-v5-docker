# Play with Symfony 5 and docker

```
cd docker

docker-compose build

docker-compose up -d

docker-compose exec php-fpm bin/console doctrine:migrations:migrate

docker-compose exec php-fpm bin/console doctrine:fixtures:load
```
