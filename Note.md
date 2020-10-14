- Install the application dependencies

  `docker-compose run --rm backend composer install`

- Initialize the application by running the init command within a container

  `docker-compose run --rm backend php /app/init`

- Start the application

  `docker-compose up -d`

- Lists the application running

  `docker-compose ps`

- Stop the apllication

  `docker-compose down -v`

- Run the migrations

  `docker-compose run --rm backend yii migrate`

- Add yii2-widget-select2

  `docker-compose run --rm backend composer require kartik-v/yii2-widget-select2 "@dev"`
