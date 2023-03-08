Build do projeto ``docker-compose up -d --build`` # todoList

Executar comandos docker:
1 docker exec setup-php composer install

2 docker exec setup-php php artisan migrate

3 docker exec -it setup-php php artisan tinker