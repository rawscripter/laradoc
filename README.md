# LARADOC

Make your life easier with laradoc.

# Build docker images and run the applications

```docker
docker-compose build
docker-compose up -d
```

## Install Laravel

laravel files will go inside src folder

```composer
docker-compose run --rm composer create-project --prefer-dist laravel/laravel .
```

And you are ready to build something amazing :) Localhost url: [http://localhost:8090](http://localhost:8090)

## To run composer commands

```docker
docker-compose run --rm composer ....
```

## To run artisan commands

```docker
docker-compose run --rm artisan ....
```

## To run npm commands

```docker
docker-compose run --rm npm ....
```

# Setup database connection

```composer
DB_CONNECTION=mysql
DB_HOST=mysql
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=laravel
```

## License

[MIT](https://choosealicense.com/licenses/mit/)

```

```
